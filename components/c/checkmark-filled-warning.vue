<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/yo-01obuo.css';
import '../../css/w/wz_fdacbr.css';
import '../../css/c/cyoweacxi.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="yo-01obuo"/><path class="wz_fdacbr"/><path class="cyoweacxi"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="carbon:checkmark-filled-warning" /></template>
