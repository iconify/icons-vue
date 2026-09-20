<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/qw4stng5y.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="qw4stng5y"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:exchange-bitcoin-line" /></template>
