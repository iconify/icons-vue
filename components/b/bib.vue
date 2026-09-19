<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/ufeehvblu.css';
import '../../css/i/io25jxifj.css';
import '../../css/g/gk58d4b-u.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<g class="ufeehvblu"><path class="io25jxifj"/><path class="gk58d4b-u"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="icon-park:bib" /></template>
