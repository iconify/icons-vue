<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/l15f58bue.css';
import '../../css/m/mxv0-rl9y.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="l15f58bue"/><path class="mxv0-rl9y"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="carbon:equal-approximately" /></template>
