<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/ft5dv1b6b.css';
import '../../css/i/imw18uqpy.css';
import '../../css/i/ijr721b7b.css';
import '../../css/q/qhj_yo_sl.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<g class="ft5dv1b6b"><path class="imw18uqpy"/><path clip-rule="evenodd" class="ijr721b7b"/><path class="qhj_yo_sl"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="icon-park:lark-one" /></template>
