<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/n1lsf0bnc.css';
import '../../css/m/maeqr4s2c.css';
import '../../css/b/bw3q8ht0l.css';
import '../../css/i/ijw3xziot.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<g clip-rule="evenodd" class="n1lsf0bnc"><path class="maeqr4s2c"/><path class="bw3q8ht0l"/><path class="ijw3xziot"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="heroicons-solid:finger-print" /></template>
