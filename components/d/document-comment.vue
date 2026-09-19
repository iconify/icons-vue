<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/i0x804ply.css';
import '../../css/f/f8hzr132d.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="i0x804ply"/><path class="f8hzr132d"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="carbon:document-comment" /></template>
