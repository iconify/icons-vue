<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/b831m4gil.css';
import '../../css/y/ymi7bmilz.css';
import '../../css/u/u7gs_rbma.css';
import '../../css/m/my6364gtl.css';
import '../../css/c/c2_0dtqer.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":72,"height":72};
const content = `<path class="b831m4gil"/><path class="ymi7bmilz"/><path class="u7gs_rbma"/><path class="my6364gtl"/><path class="c2_0dtqer"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="openmoji:hourglass-not-done" /></template>
