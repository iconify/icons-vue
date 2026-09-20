<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/hfyllwbid.css';
import '../../css/y/yklxlcb9b.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":256,"height":256};
const content = `<path class="hfyllwbid"/><path class="yklxlcb9b"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-icon-theme:blink" /></template>
