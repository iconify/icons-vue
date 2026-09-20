<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/wgmv_dbrx.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="wgmv_dbrx"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="vaadin:grid-big" /></template>
