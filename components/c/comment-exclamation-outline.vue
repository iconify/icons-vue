<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/ft5dv1b6b.css';
import '../../css/p/pj3mqtrfu.css';
import '../../css/k/kqg7zabzh.css';
import '../../css/g/g012uybcj.css';
import '../../css/f/fudyny6gj.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":80,"height":80};
const content = `<g class="ft5dv1b6b"><path class="pj3mqtrfu"/><path clip-rule="evenodd" class="kqg7zabzh"/><path class="g012uybcj"/><path clip-rule="evenodd" class="fudyny6gj"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="glyphs:comment-exclamation-outline" /></template>
