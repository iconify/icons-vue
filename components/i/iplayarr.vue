<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/ppubembly.css';
import '../../css/h/h9fsqi6ij.css';
import '../../css/d/dup3v4bcs.css';
import '../../css/e/evhgdbbjt.css';
import '../../css/j/j2p8_jaiw.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<circle class="ppubembly"/><path class="h9fsqi6ij"/><path class="dup3v4bcs"/><path class="evhgdbbjt"/><path class="j2p8_jaiw"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:iplayarr" /></template>
