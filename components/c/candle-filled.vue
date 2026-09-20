<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/aviom1boc.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="aviom1boc"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="reicon:candle-filled" /></template>
