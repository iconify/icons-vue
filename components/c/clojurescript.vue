<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/cuyn6tgcc.css';
import '../../css/d/dilm5cb8z.css';
import '../../css/k/ktk7rfg2u.css';
import '../../css/v/vyxuym72m.css';
import '../../css/c/c_ime9bag.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":128,"height":128};
const content = `<g class="cuyn6tgcc"><path class="dilm5cb8z"/><g class="ktk7rfg2u"><path class="vyxuym72m"/><path class="c_ime9bag"/></g></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="thesvg:clojurescript" /></template>
