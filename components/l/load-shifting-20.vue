<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/fl-um2bwn.css';
import '../../css/x/xhea0tlij.css';
import '../../css/j/j9rmcs4ak.css';
import '../../css/j/jufp2rs3q.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="fl-um2bwn"/><path class="xhea0tlij"/><path class="j9rmcs4ak"/><path class="jufp2rs3q"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:load-shifting-20" /></template>
