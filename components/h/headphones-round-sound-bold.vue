<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/x35xwlb8d.css';
import '../../css/z/zs6jv9bdw.css';
import '../../css/x/xz-3bfbvl.css';
import '../../css/l/l07j66hls.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="x35xwlb8d"/><path clip-rule="evenodd" class="zs6jv9bdw"/><path clip-rule="evenodd" class="xz-3bfbvl"/><path clip-rule="evenodd" class="l07j66hls"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:headphones-round-sound-bold" /></template>
