<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/s9nmekbvz.css';
import '../../css/h/hgn-75b4t.css';
import '../../css/z/zl0fbyblg.css';
import '../../css/h/h900o1u8p.css';
import '../../css/k/k32ibobjl.css';
import '../../css/f/f545reb7b.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="s9nmekbvz"><path class="hgn-75b4t wm-deco"/><path class="wm-deco zl0fbyblg"/><path class="h900o1u8p wm-deco"/><path class="k32ibobjl wm-k"/><path class="f545reb7b wm-a"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="withicons:baguette-blueprint" /></template>
