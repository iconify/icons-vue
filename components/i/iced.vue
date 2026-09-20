<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/rss06kbzg.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="rss06kbzg"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="thesvg-color:iced" /></template>
