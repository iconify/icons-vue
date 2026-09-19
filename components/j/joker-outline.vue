<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/bi12bsetm.css';
import '../../css/a/a3c8mjbsl.css';
import '../../css/i/isvo6rdbz.css';
import '../../css/r/r8f-8remn.css';
import '../../css/d/dbnkfibrk.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":80,"height":80};
const content = `<g clip-rule="evenodd" class="bi12bsetm"><path class="a3c8mjbsl"/><path class="isvo6rdbz"/><path class="r8f-8remn"/><path class="dbnkfibrk"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="glyphs:joker-outline" /></template>
