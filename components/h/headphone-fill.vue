<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/n7jzhi2jd.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="n7jzhi2jd"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:headphone-fill" /></template>
