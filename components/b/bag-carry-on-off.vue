<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/dvg7dvb_w.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="dvg7dvb_w"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:bag-carry-on-off" /></template>
