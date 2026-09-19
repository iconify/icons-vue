<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/l4-y6jbck.css';
import '../../css/h/hu2vwjy5d.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="l4-y6jbck"/><path class="hu2vwjy5d"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="bx:bxs-microphone-off" /></template>
