<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/ft5dv1b6b.css';
import '../../css/x/x6-u63tpe.css';
import '../../css/s/s-f1sxbzj.css';
import '../../css/n/ngw05cc0t.css';
import '../../css/i/ijey5tl3d.css';
import '../../css/u/uebyq5hhe.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":24};
const content = `<g class="ft5dv1b6b"><path clip-rule="evenodd" class="x6-u63tpe"/><path clip-rule="evenodd" class="s-f1sxbzj"/><path class="ngw05cc0t"/><path class="ijey5tl3d"/><path clip-rule="evenodd" class="uebyq5hhe"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="flagpack:ag" /></template>
