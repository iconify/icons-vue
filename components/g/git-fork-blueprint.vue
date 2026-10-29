<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/s9nmekbvz.css';
import '../../css/p/pqefv2b9w.css';
import '../../css/e/e4kubqbgr.css';
import '../../css/c/cf3uzcrzx.css';
import '../../css/o/oeinx3baj.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="s9nmekbvz"><path class="pqefv2b9w wm-deco"/><path class="e4kubqbgr wm-deco"/><path class="cf3uzcrzx wm-deco"/><path class="oeinx3baj"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="withicons:git-fork-blueprint" /></template>
