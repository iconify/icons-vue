<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/s16uusb2w.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="s16uusb2w"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:card-multiple-outline" /></template>
