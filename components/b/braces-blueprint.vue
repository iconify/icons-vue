<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/s9nmekbvz.css';
import '../../css/p/p56rhtbce.css';
import '../../css/b/bxjv56brc.css';
import '../../css/a/awy7zdblf.css';
import '../../css/b/b_239qmsy.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="s9nmekbvz"><path class="p56rhtbce wm-deco"/><path class="bxjv56brc wm-deco"/><path class="awy7zdblf"/><path class="b_239qmsy"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="withicons:braces-blueprint" /></template>
