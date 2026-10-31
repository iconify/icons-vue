<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/ft5dv1b6b.css';
import '../../css/n/npt9ygbzn.css';
import '../../css/p/pk-y8fbct.css';
import '../../css/a/aeid6kvpe.css';
import '../../css/c/ch4k4jb6h.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><path class="npt9ygbzn wm-k"/><path class="pk-y8fbct wm-deco"/><path class="aeid6kvpe wm-k"/><path class="ch4k4jb6h wm-shadow"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="withicons-valentine:gem" /></template>
