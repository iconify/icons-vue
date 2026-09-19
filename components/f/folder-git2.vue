<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/ipq1z-bjh.css';
import '../../css/d/dr3en4b5i.css';
import '../../css/i/ighay767r.css';
import '../../css/d/du96umduy.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ipq1z-bjh"><path class="dr3en4b5i"/><path class="ighay767r"/><path class="du96umduy"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="hugeicons:folder-git2" /></template>
