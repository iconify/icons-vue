<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/i6d5tp4hc.css';
import '../../css/a/aji04yosq.css';
import '../../css/w/wmxx11b3l.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="i6d5tp4hc"/><path class="aji04yosq"/><path class="wmxx11b3l"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="tdesign:animation-filled" /></template>
