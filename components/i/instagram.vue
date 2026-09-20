<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/ft5dv1b6b.css';
import '../../css/a/ak_npccsm.css';
import '../../css/n/n14m7qbat.css';
import '../../css/s/sb5o2gexg.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><rect class="ak_npccsm"/><circle class="n14m7qbat"/><circle class="sb5o2gexg"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="proicons:instagram" /></template>
