<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/ll0vpnbtt.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ll0vpnbtt"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ri:expand-diagonal-2-fill" /></template>
