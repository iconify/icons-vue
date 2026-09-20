<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/uejcfd1cs.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="uejcfd1cs"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-plump:end-point-diamond-solid" /></template>
