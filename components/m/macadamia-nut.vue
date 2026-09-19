<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/y_xj2ldud.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="y_xj2ldud"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="icon-park-outline:macadamia-nut" /></template>
