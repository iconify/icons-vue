<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/tds1kzquw.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":640,"height":640};
const content = `<path class="tds1kzquw"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fa7-brands:btc" /></template>
