<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/ctm2pnp-v.css';
import '../../css/p/p74o-abky.css';
import '../../css/o/o-o_j-mgr.css';
import '../../css/u/u44_1dbap.css';
import '../../css/y/yx2pxubfz.css';
import '../../css/o/oggaayjxd.css';
import '../../css/k/k67y7pbaq.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ctm2pnp-v wm-shadow"/><path class="p74o-abky wm-k"/><path class="o-o_j-mgr wm-k"/><path class="u44_1dbap wm-k"/><path class="wm-k yx2pxubfz"/><path class="oggaayjxd wm-k"/><path class="k67y7pbaq wm-shine"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="withicons-pastel:corner-up-left" /></template>
