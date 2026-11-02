<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/uubay8r-f.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="uubay8r-f"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:currency-bitcoin-line" /></template>
