<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/ft5dv1b6b.css';
import '../../css/o/onwa8sb2c.css';
import '../../css/k/kjwymwxwh.css';
import '../../css/i/iur_obb4v.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":80,"height":80};
const content = `<g class="ft5dv1b6b"><path class="onwa8sb2c"/><path class="kjwymwxwh"/><path class="iur_obb4v"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="glyphs:dollar-bills-duo" /></template>
