<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/xn5eo9bqs.css';
import '../../css/s/sxnyd4ewi.css';
import '../../css/b/b-p73fn2z.css';
import '../../css/v/v7tp-zgpi.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="xn5eo9bqs"><path class="sxnyd4ewi"/><path class="b-p73fn2z"/><path class="v7tp-zgpi"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="matita:globe" /></template>
