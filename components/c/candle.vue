<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/dkh_dk9bo.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="dkh_dk9bo"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-sharp:candle" /></template>
