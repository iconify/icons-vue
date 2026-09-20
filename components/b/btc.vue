<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/xo8yglb7w.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="xo8yglb7w"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lineicons:btc" /></template>
