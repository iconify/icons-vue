<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/flen3tbdj.css';
import '../../css/t/tk26rl12m.css';
import '../../css/t/t0axslt3v.css';
import '../../css/o/o1r9vkb7d.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="flen3tbdj"><rect class="tk26rl12m"/><path class="t0axslt3v"/><path class="o1r9vkb7d"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="codex:copy-check" /></template>
