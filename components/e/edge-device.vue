<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/czq8nj3ot.css';
import '../../css/t/t-nlx2bxo.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="czq8nj3ot"/><path class="t-nlx2bxo"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="carbon:edge-device" /></template>
