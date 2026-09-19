<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/ft5dv1b6b.css';
import '../../css/n/nedktqbjv.css';
import '../../css/g/gysbfcbnp.css';
import '../../css/p/pvkov0bch.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<g class="ft5dv1b6b"><path class="nedktqbjv"/><path class="gysbfcbnp"/><path clip-rule="evenodd" class="pvkov0bch"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="icon-park:help" /></template>
