<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/c_z8u2bhx.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":2048,"height":1344};
const content = `<path class="c_z8u2bhx"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="vs:fish" /></template>
