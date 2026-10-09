<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/lcx_6xb7j.css';
import '../../css/w/wzhdi44yk.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="lcx_6xb7j"/><path class="wzhdi44yk"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:bbq-20-bold" /></template>
