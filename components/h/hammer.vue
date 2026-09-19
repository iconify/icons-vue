<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/ft5dv1b6b.css';
import '../../css/d/d4bvf14zw.css';
import '../../css/y/y2hjzlb3l.css';
import '../../css/h/h7ej-dbml.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<g class="ft5dv1b6b"><path class="d4bvf14zw"/><path class="y2hjzlb3l"/><path class="h7ej-dbml"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent-emoji-flat:hammer" /></template>
