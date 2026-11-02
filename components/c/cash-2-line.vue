<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/uutmmvbht.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="uutmmvbht"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:cash-2-line" /></template>
