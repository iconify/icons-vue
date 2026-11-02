<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/ql2n6wb7r.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ql2n6wb7r"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:capricorn-line" /></template>
