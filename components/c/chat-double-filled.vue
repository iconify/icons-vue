<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/rh33njbcs.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="rh33njbcs"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="tdesign:chat-double-filled" /></template>
