<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/xqga1ycio.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="xqga1ycio"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="reicon:emoji-happy-filled" /></template>
