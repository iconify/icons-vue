<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/d4kq9bc3r.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="d4kq9bc3r"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:exchange-bitcoin-fill" /></template>
