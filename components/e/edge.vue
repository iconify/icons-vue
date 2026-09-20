<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/r3xu5kyvp.css';
import '../../css/r/re5rgnbfo.css';
import '../../css/q/qguzlhbxh.css';
import '../../css/j/jf456eeoy.css';
import '../../css/j/jn8qy4bru.css';
import '../../css/c/c88l71byj.css';
import '../../css/x/xrhnvkx6q.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":72,"height":72};
const content = `<path class="r3xu5kyvp"/><path clip-rule="evenodd" class="re5rgnbfo"/><path clip-rule="evenodd" class="qguzlhbxh"/><path clip-rule="evenodd" class="jf456eeoy"/><g class="jn8qy4bru"><path class="c88l71byj"/><path class="xrhnvkx6q"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="openmoji:edge" /></template>
