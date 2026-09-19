<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/ja3d0vbny.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ja3d0vbny"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="gg:arrows-scroll-v" /></template>
