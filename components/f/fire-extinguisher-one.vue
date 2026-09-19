<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/ufeehvblu.css';
import '../../css/i/iekxguumk.css';
import '../../css/e/e6kad7bsr.css';
import '../../css/p/pp7jd5l6t.css';
import '../../css/w/w5s9in16w.css';
import '../../css/a/ag-gnrc5k.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<g class="ufeehvblu"><path class="iekxguumk"/><path class="e6kad7bsr"/><rect class="pp7jd5l6t"/><path class="w5s9in16w"/><path class="ag-gnrc5k"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="icon-park:fire-extinguisher-one" /></template>
