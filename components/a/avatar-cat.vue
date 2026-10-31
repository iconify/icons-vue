<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/ft5dv1b6b.css';
import '../../css/b/bfyb8bkre.css';
import '../../css/u/u2p9y8kpc.css';
import '../../css/q/qys2q-blz.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><path class="bfyb8bkre wm-k"/><path class="u2p9y8kpc wm-shine"/><path class="qys2q-blz wm-shine"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="withicons-lunar:avatar-cat" /></template>
