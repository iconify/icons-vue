<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/hit3bi0-v.css';
import '../../css/p/p-3d8dotc.css';
import '../../css/e/ec9lvsxkj.css';
import '../../css/z/zwf0cly4t.css';
import '../../css/j/jgdiew26a.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<g class="hit3bi0-v"><path class="p-3d8dotc"/><path class="ec9lvsxkj"/><path clip-rule="evenodd" class="zwf0cly4t"/><path class="jgdiew26a"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="icon-park-outline:adobe-photoshop" /></template>
