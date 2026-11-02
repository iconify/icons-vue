<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/lhz-0n1hf.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="lhz-0n1hf"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:currency-bitcoin-2-line" /></template>
