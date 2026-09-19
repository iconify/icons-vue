<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/jx0p4fbya.css';
import '../../css/s/seuormdxt.css';
import '../../css/b/br8th3blo.css';
import '../../css/b/buhh-db0h.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="jx0p4fbya"><path class="seuormdxt"/><path class="br8th3blo"/><path class="buhh-db0h"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="hugeicons:gas-pipe" /></template>
