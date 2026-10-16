<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/x3cm5wgot.css';
import '../../css/n/n3396pgch.css';
import '../../css/n/n-sk7ob6c.css';
import '../../css/r/r243x0bvm.css';
import '../../css/u/uve5exj4g.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="x3cm5wgot"/><path class="n3396pgch"/><path class="n-sk7ob6c"/><path class="r243x0bvm"/><path class="uve5exj4g"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:busbar-20-bold" /></template>
