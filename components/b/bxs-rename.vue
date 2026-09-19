<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/gxv-nrbxk.css';
import '../../css/e/e03sdjqcb.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="gxv-nrbxk"/><path class="e03sdjqcb"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="bx:bxs-rename" /></template>
