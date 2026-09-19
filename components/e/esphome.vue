<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/t88ywcbrq.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="t88ywcbrq"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="cbi:esphome" /></template>
