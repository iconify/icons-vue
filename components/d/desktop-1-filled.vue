<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/nsfig2t_x.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="nsfig2t_x"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="tdesign:desktop-1-filled" /></template>
