<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/s9nmekbvz.css';
import '../../css/o/otia_qs9v.css';
import '../../css/d/dk36_qbfc.css';
import '../../css/y/yltf94bxm.css';
import '../../css/c/chfexdi1f.css';
import '../../css/d/drdv4ab-w.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="s9nmekbvz"><path class="otia_qs9v wm-deco"/><path class="dk36_qbfc wm-deco"/><path class="wm-k yltf94bxm"/><path class="chfexdi1f wm-a"/><path class="drdv4ab-w wm-k"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="withicons:chevron-first-blueprint" /></template>
