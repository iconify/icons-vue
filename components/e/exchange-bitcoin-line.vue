<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/myth_xz5t.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="myth_xz5t"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:exchange-bitcoin-line" /></template>
