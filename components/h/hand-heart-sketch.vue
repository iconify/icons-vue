<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/tczw_hbsg.css';
import '../../css/a/aajok45mv.css';
import '../../css/l/le5q5c42g.css';
import '../../css/m/mhb-ipbjs.css';
import '../../css/d/dgk7tnbpd.css';
import '../../css/c/cqpvlqbjo.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="tczw_hbsg"><path class="aajok45mv"/><path class="le5q5c42g wm-k"/><path class="mhb-ipbjs wm-a"/><path class="dgk7tnbpd wm-k"/><path class="cqpvlqbjo wm-a"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="withicons:hand-heart-sketch" /></template>
