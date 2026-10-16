<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/m4p14_bkx.css';
import '../../css/p/pacy82nug.css';
import '../../css/x/xftc_vblp.css';
import '../../css/k/kpc_4jb4q.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="m4p14_bkx"/><path class="pacy82nug"/><path class="xftc_vblp"/><path class="kpc_4jb4q"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:load-cell-20-bold" /></template>
