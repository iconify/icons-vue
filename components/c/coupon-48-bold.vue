<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/u-7-2mbbf.css';
import '../../css/u/u7xulot5t.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="u-7-2mbbf"/><path class="u7xulot5t"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:coupon-48-bold" /></template>
