<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/sqag7l0gr.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="sqag7l0gr"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="zondicons:battery-low" /></template>
