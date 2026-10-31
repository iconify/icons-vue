<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/xd1vp8bpc.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="xd1vp8bpc"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="withicons:chess-gloss" /></template>
