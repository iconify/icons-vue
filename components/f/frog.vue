<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/fi284xblo.css';
import '../../css/r/rl9nm6b5b.css';
import '../../css/j/j3g_okd9a.css';
import '../../css/s/s7hiajbok.css';
import '../../css/r/rryepq1cz.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="fi284xblo"/><path class="rl9nm6b5b"/><path class="j3g_okd9a"/><path class="s7hiajbok"/><path class="rryepq1cz"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fxemoji:frog" /></template>
