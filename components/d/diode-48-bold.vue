<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/ht2v78f-m.css';
import '../../css/u/u431zobpm.css';
import '../../css/c/cbzm5ebwg.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="ht2v78f-m"/><path class="u431zobpm"/><path class="cbzm5ebwg"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:diode-48-bold" /></template>
