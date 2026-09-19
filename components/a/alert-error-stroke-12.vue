<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/h01tyzbfu.css';
import '../../css/o/ohlpaj_qx.css';
import '../../css/i/i6lvci1zi.css';
import '../../css/e/ejq2wacjo.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":12,"height":12};
const content = `<g class="h01tyzbfu"><circle class="ohlpaj_qx"/><path class="i6lvci1zi"/></g><circle class="ejq2wacjo"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="garden:alert-error-stroke-12" /></template>
