<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/cuyn6tgcc.css';
import '../../css/l/lxnzn9nmw.css';
import '../../css/f/fcqvb8bsm.css';
import '../../css/d/d1fm_b5bb.css';
import '../../css/l/lty7dabjq.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="cuyn6tgcc"><path class="lxnzn9nmw"/><path class="fcqvb8bsm"/><path class="d1fm_b5bb"/><path class="lty7dabjq"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:hamburger-menu-bold-duotone" /></template>
