<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/ft5dv1b6b.css';
import '../../css/y/y42c4vbzm.css';
import '../../css/a/a4kmvabwe.css';
import '../../css/z/zehkdc87c.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<g class="ft5dv1b6b"><path class="y42c4vbzm"/><path class="a4kmvabwe"/><path class="zehkdc87c"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent-emoji-flat:feather" /></template>
