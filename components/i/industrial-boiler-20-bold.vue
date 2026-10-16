<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/lz93yvfkk.css';
import '../../css/w/wgr1h7bfy.css';
import '../../css/y/yfoxxnbix.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="lz93yvfkk"/><path class="wgr1h7bfy"/><path class="yfoxxnbix"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:industrial-boiler-20-bold" /></template>
