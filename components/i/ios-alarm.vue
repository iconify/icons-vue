<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/mmi-16b0h.css';
import '../../css/l/l544h_tbr.css';
import '../../css/l/l-m2k2bsw.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="mmi-16b0h"/><path class="l544h_tbr"/><g><path class="l-m2k2bsw"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ion:ios-alarm" /></template>
