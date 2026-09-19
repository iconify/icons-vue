<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/ipq1z-bjh.css';
import '../../css/j/ja_r16b-t.css';
import '../../css/h/hbxhkzysn.css';
import '../../css/z/zit5rebxl.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ipq1z-bjh"><path class="ja_r16b-t"/><path class="hbxhkzysn"/><path class="zit5rebxl"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="hugeicons:cup-soda" /></template>
