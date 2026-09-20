<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/ef6k_cc-g.css';
import '../../css/t/t7his9f7x.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path clip-rule="evenodd" class="ef6k_cc-g"/><path class="t7his9f7x"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lsicon:camera-filled" /></template>
