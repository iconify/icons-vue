<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/xsotg_bjg.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="xsotg_bjg"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="bx:bxs-shield" /></template>
