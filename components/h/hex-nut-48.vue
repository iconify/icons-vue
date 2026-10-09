<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/f77e97noo.css';
import '../../css/c/cmhnqibcc.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="f77e97noo"/><path class="cmhnqibcc"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:hex-nut-48" /></template>
