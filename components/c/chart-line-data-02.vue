<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/jx0p4fbya.css';
import '../../css/x/x3_k44z0a.css';
import '../../css/s/ssww1kb2i.css';
import '../../css/o/o2r20265f.css';
import '../../css/i/iy1a8hbwf.css';
import '../../css/u/uvss_uvsg.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="jx0p4fbya"><circle class="x3_k44z0a"/><circle class="ssww1kb2i"/><circle class="o2r20265f"/><path class="iy1a8hbwf"/><path class="uvss_uvsg"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="hugeicons:chart-line-data-02" /></template>
