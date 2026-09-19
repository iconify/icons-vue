<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/jx0p4fbya.css';
import '../../css/e/ez3g9wb-c.css';
import '../../css/u/u5m8n7-ni.css';
import '../../css/s/sf-e43b5o.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="jx0p4fbya"><path class="ez3g9wb-c"/><path class="u5m8n7-ni"/><path class="sf-e43b5o"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="hugeicons:cards-02" /></template>
