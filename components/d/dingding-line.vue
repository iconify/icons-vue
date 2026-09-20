<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/wbo7v2b1z.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="wbo7v2b1z"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ri:dingding-line" /></template>
