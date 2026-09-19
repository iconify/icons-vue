<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/cc0c_gq-d.css';
import '../../css/s/sx0qtzbwt.css';
import '../../css/l/l5a55bckk.css';
import '../../css/n/nspmw7h7l.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="cc0c_gq-d"/><path class="sx0qtzbwt"/><path class="l5a55bckk"/><path class="nspmw7h7l"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fxemoji:hampster" /></template>
