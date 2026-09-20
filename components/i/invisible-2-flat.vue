<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/em7xvwbpj.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="em7xvwbpj"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-plump-color:invisible-2-flat" /></template>
