<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/nz_20wbpz.css';
import '../../css/i/i5hd2ab8w.css';
import '../../css/u/ujbxjmbjk.css';
import '../../css/a/a3tlaubzd.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<g class="nz_20wbpz"><path class="i5hd2ab8w"/><path class="ujbxjmbjk"/><path class="a3tlaubzd"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="icon-park-solid:keyline" /></template>
