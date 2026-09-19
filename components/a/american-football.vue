<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/ati6izcqr.css';
import '../../css/o/oeud78yma.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="ati6izcqr"/><path class="oeud78yma"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="cil:american-football" /></template>
