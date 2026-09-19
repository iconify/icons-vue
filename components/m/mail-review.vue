<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/ufeehvblu.css';
import '../../css/t/t-lmtqbvy.css';
import '../../css/c/czwtscbxu.css';
import '../../css/f/fz7nbcc5u.css';
import '../../css/x/x2v1nbbxv.css';
import '../../css/m/m4vdscbwk.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<g class="ufeehvblu"><path class="t-lmtqbvy"/><path class="czwtscbxu"/><path class="fz7nbcc5u"/><path class="x2v1nbbxv"/><path class="m4vdscbwk"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="icon-park:mail-review" /></template>
