<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/wf3u6-btt.css';
import '../../css/d/dcscq4zhc.css';
import '../../css/u/umtu9dbhb.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="wf3u6-btt"/><path class="dcscq4zhc"/><path class="umtu9dbhb"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:follow-line" /></template>
