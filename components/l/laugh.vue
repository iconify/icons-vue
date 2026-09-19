<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/jx0p4fbya.css';
import '../../css/g/gvj669z4w.css';
import '../../css/z/z3exurbqq.css';
import '../../css/r/r6k04cbja.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="jx0p4fbya"><path class="gvj669z4w"/><path class="z3exurbqq"/><circle class="r6k04cbja"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="hugeicons:laugh" /></template>
