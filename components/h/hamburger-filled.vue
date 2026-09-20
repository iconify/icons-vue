<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/zngysg_hj.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="zngysg_hj"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="tdesign:hamburger-filled" /></template>
