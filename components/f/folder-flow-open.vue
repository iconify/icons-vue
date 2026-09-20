<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/s27ky2-ij.css';
import '../../css/g/gm4az_b0m.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="s27ky2-ij"/><path class="gm4az_b0m"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-icon-theme:folder-flow-open" /></template>
