<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/giagzkb_z.css';
import '../../css/q/qgd51yb9o.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="giagzkb_z"/><path class="qgd51yb9o"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="flat-color-icons:left-down" /></template>
