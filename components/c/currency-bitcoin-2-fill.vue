<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/i-ulnd4tc.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="i-ulnd4tc"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:currency-bitcoin-2-fill" /></template>
