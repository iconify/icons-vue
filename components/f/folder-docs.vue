<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/hcjmcxbsc.css';
import '../../css/x/xtenr_bwi.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="hcjmcxbsc"/><path class="xtenr_bwi"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-icon-theme:folder-docs" /></template>
