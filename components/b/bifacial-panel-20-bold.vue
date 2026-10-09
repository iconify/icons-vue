<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/pywiv_biz.css';
import '../../css/q/qv4_abryf.css';
import '../../css/c/c0wsg8bse.css';
import '../../css/y/yfoxxnbix.css';
import '../../css/r/rbeht2tnq.css';
import '../../css/i/ivikgibsc.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="pywiv_biz"/><path class="qv4_abryf"/><path class="c0wsg8bse"/><path class="yfoxxnbix"/><path class="rbeht2tnq"/><path class="ivikgibsc"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:bifacial-panel-20-bold" /></template>
