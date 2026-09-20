<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/ft5dv1b6b.css';
import '../../css/o/o0n9q_5jv.css';
import '../../css/b/bate30btk.css';
import '../../css/r/r5k-ofblz.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><circle class="o0n9q_5jv"/><path class="bate30btk"/><path clip-rule="evenodd" class="r5k-ofblz"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lets-icons:file-dock-search-fill" /></template>
