<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/xv42s-bwo.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="xv42s-bwo"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconamoon:attachment-duotone" /></template>
