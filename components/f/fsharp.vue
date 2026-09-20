<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/lrm90vr2z.css';
import '../../css/r/rvlpixg0l.css';
import '../../css/d/dgch7ibmy.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":500,"height":500};
const content = `<path class="lrm90vr2z"/><path class="rvlpixg0l"/><path class="dgch7ibmy"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-icon-theme:fsharp" /></template>
