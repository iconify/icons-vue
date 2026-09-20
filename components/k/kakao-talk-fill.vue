<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/xglfi1bww.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="xglfi1bww"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:kakao-talk-fill" /></template>
