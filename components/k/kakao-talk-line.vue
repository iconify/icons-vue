<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/gdd12bcok.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="gdd12bcok"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ri:kakao-talk-line" /></template>
