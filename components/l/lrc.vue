<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/so9w1vbig.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="so9w1vbig"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="token:lrc" /></template>
