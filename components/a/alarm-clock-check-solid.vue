<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/n1lsf0bnc.css';
import '../../css/t/tf3hozrsc.css';
import '../../css/b/bwvqb54kv.css';
import '../../css/u/u06ygo3ib.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="n1lsf0bnc"><path class="tf3hozrsc"/><path class="bwvqb54kv wm-a"/><path class="u06ygo3ib wm-s"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="withicons:alarm-clock-check-solid" /></template>
