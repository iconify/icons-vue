<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/xdgev-rkf.css';
import '../../css/n/nym97nevk.css';
import '../../css/u/u-bp7mb3x.css';
import '../../css/b/bmo7zrg8h.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="xdgev-rkf"/><path class="nym97nevk"/><path class="u-bp7mb3x"/><path class="bmo7zrg8h"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="flag:gh-1x1" /></template>
