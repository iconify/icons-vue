<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/kpngxw3vl.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="kpngxw3vl"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:circle-arrow-out-up-left-line" /></template>
