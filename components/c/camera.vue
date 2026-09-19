<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/bof311bis.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="bof311bis"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="gridicons:camera" /></template>
