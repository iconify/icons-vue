<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/n1dnwesbx.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="n1dnwesbx"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="dashicons:editor-ol-rtl" /></template>
