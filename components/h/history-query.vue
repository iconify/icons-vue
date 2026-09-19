<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/hit3bi0-v.css';
import '../../css/m/mhrr42g8a.css';
import '../../css/p/p3qnucb9w.css';
import '../../css/l/l7sdvlbrp.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<g class="hit3bi0-v"><path class="mhrr42g8a"/><circle class="p3qnucb9w"/><path class="l7sdvlbrp"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="icon-park-solid:history-query" /></template>
