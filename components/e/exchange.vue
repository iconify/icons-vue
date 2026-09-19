<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/y05ccfbwe.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":1792,"height":1376};
const content = `<path class="y05ccfbwe"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fa:exchange" /></template>
