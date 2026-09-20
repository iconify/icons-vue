<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/ce_mi-b2c.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path clip-rule="evenodd" class="ce_mi-b2c"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-plump:high-speed-train-side-solid" /></template>
