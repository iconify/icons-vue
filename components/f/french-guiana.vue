<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/r6ysyvb8h.css';
import '../../css/w/wjt581t1z.css';
import '../../css/q/qfcqjabfa.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":30,"height":24};
const content = `<path class="r6ysyvb8h"/><path class="wjt581t1z"/><path class="qfcqjabfa"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="tabler-flags:french-guiana" /></template>
