<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/wamyv4bnc.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="wamyv4bnc"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="tdesign:ink-filled" /></template>
