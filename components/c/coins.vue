<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/hntgybcog.css';
import '../../css/w/wmbc14diz.css';
import '../../css/e/escw9vdfc.css';
import '../../css/h/hrfy6hbni.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="wmbc14diz"/><path class="escw9vdfc"/><path class="hrfy6hbni"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoir:coins" /></template>
