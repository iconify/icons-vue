<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/cuyn6tgcc.css';
import '../../css/x/xebc19bjy.css';
import '../../css/g/gf6s6zlii.css';
import '../../css/y/ypt4qqd3n.css';
import '../../css/f/fb6wotbsm.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<g class="cuyn6tgcc"><path class="xebc19bjy"/><path class="gf6s6zlii"/><path class="ypt4qqd3n"/><path class="fb6wotbsm"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="healthicons:close-policy-gaps-alt" /></template>
