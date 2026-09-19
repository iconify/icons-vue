<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/kccx5mbrd.css';
import '../../css/c/cigvp3btk.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="kccx5mbrd"/><path class="cigvp3btk"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="carbon:gas-station-filled" /></template>
