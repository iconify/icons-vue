<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/h695rk-bi.css';
import '../../css/y/yfbn82bpl.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="h695rk-bi"/><path class="yfbn82bpl"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:exchange-bitcoin-2-fill" /></template>
