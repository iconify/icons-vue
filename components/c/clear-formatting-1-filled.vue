<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/zyd9tlbpe.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="zyd9tlbpe"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="tdesign:clear-formatting-1-filled" /></template>
