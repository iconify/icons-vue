<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/nz_20wbpz.css';
import '../../css/y/y5f1ucbki.css';
import '../../css/z/zfouoybeb.css';
import '../../css/c/c8tjlaclr.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<g class="nz_20wbpz"><path class="y5f1ucbki"/><path class="zfouoybeb"/><path class="c8tjlaclr"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="icon-park-solid:lotion" /></template>
