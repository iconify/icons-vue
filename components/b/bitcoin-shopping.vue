<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/jx0p4fbya.css';
import '../../css/w/wkje7hb8n.css';
import '../../css/p/pg7s9yb5j.css';
import '../../css/q/qozo6tb2l.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="jx0p4fbya"><path class="wkje7hb8n"/><path class="pg7s9yb5j"/><path class="qozo6tb2l"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="hugeicons:bitcoin-shopping" /></template>
