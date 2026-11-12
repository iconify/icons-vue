<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/fw2m33brc.css';
import '../../css/h/h78ewob-k.css';
import '../../css/p/pg98fbbdj.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="fw2m33brc"/><path class="h78ewob-k"/><path class="pg98fbbdj"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:ksuite-docs-light" /></template>
