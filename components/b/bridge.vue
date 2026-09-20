<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/zoa2debvg.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="zoa2debvg"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="tdesign:bridge" /></template>
