<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/cuyn6tgcc.css';
import '../../css/s/sctsa_k0p.css';
import '../../css/j/jyjxt1bxt.css';
import '../../css/c/c639ihldk.css';
import '../../css/t/t5k8km11l.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<g class="cuyn6tgcc"><path class="sctsa_k0p"/><path clip-rule="evenodd" class="jyjxt1bxt"/><path clip-rule="evenodd" class="c639ihldk"/><path clip-rule="evenodd" class="t5k8km11l"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pepicons:clock-print" /></template>
