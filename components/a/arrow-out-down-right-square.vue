<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/k5pr-v-xw.css';
import '../../css/y/yf1avm6ta.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="k5pr-v-xw"/><path class="yf1avm6ta"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="boxicons:arrow-out-down-right-square" /></template>
