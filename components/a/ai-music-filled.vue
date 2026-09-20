<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/sl8ymfb2m.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":25,"height":24};
const content = `<path class="sl8ymfb2m"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="tdesign:ai-music-filled" /></template>
