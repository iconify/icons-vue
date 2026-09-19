<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/ft5dv1b6b.css';
import '../../css/f/f_8dibbbr.css';
import '../../css/n/n9cjt0gfj.css';
import '../../css/h/h16w2w8rj.css';
import '../../css/d/do5q9cj2u.css';
import '../../css/d/dbn_3t14u.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<g class="ft5dv1b6b"><path class="f_8dibbbr"/><path class="n9cjt0gfj"/><path class="h16w2w8rj"/><path class="do5q9cj2u"/><path class="dbn_3t14u"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent-emoji-flat:cat" /></template>
