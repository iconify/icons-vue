<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/tczw_hbsg.css';
import '../../css/c/cvk1ilb9q.css';
import '../../css/g/gkeixvvic.css';
import '../../css/c/cpnpjfb3t.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="tczw_hbsg"><path class="cvk1ilb9q wm-k"/><path class="gkeixvvic wm-k"/><path class="cpnpjfb3t wm-a"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="withicons:holly-sketch" /></template>
