<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/w63i2sb5q.css';
import '../../css/f/f6sqxlbwl.css';
import '../../css/j/j2p94mlao.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="w63i2sb5q"/><path class="f6sqxlbwl"/><path class="j2p94mlao"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="boxicons:layers-down-right-filled" /></template>
