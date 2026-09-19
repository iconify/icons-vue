<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/iqjhhacny.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":1536,"height":1536};
const content = `<path class="iqjhhacny"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fa:arrow-circle-o-left" /></template>
