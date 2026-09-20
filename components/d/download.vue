<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/wg_r_uvrh.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="wg_r_uvrh"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="nimbus:download" /></template>
