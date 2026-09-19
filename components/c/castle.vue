<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/nz_20wbpz.css';
import '../../css/k/k0phntbpf.css';
import '../../css/f/f78qppjnj.css';
import '../../css/g/g_i87xbuh.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<g class="nz_20wbpz"><path class="k0phntbpf"/><path class="f78qppjnj"/><path class="g_i87xbuh"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="icon-park-solid:castle" /></template>
