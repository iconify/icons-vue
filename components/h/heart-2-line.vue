<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/zd2lh0b1m.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="zd2lh0b1m"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ri:heart-2-line" /></template>
