<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/tl5m1kbcx.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="tl5m1kbcx"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:glass" /></template>
