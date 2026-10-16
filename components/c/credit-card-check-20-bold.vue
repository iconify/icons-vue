<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/z53z8i3hj.css';
import '../../css/y/yd1_zhbpd.css';
import '../../css/s/sh06c0bcw.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="z53z8i3hj"/><path class="yd1_zhbpd"/><path class="sh06c0bcw"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:credit-card-check-20-bold" /></template>
