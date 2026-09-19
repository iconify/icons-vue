<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/ft5dv1b6b.css';
import '../../css/d/d7zy9r0hm.css';
import '../../css/j/j98dcnb4b.css';
import '../../css/r/r0g01zbje.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<g class="ft5dv1b6b"><path class="d7zy9r0hm"/><path class="j98dcnb4b"/><path class="r0g01zbje"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent-emoji-flat:bookmark" /></template>
