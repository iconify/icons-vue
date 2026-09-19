<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/fod670bai.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":640,"height":512};
const content = `<path class="fod670bai"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fa6-solid:hand-sparkles" /></template>
