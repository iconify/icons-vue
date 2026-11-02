<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/i6o45aboc.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="i6o45aboc"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:magnet-fill" /></template>
