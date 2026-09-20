<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/hg53enbin.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="hg53enbin"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ri:archive-drawer-line" /></template>
