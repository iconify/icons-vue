<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/bi12bsetm.css';
import '../../css/y/yijrflb7c.css';
import '../../css/p/pvfkiacfy.css';
import '../../css/h/h3t3w5b6q.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":14,"height":14};
const content = `<g clip-rule="evenodd" class="bi12bsetm"><path class="yijrflb7c"/><path class="pvfkiacfy"/><path class="h3t3w5b6q"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-color:chess-king-flat" /></template>
