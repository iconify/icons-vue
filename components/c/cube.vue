<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/mgv6f4bkh.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="mgv6f4bkh"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="carbon:cube" /></template>
