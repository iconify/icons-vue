<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/lmaogdb0l.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="lmaogdb0l"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:clock-time-six" /></template>
