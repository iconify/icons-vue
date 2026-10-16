<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/a1z2bma3g.css';
import '../../css/q/qhpa06bqs.css';
import '../../css/s/sksczibjq.css';
import '../../css/z/z1omxobhi.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="a1z2bma3g"/><path class="qhpa06bqs"/><path class="sksczibjq"/><path class="z1omxobhi"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:greenhouse-effect-20-bold" /></template>
