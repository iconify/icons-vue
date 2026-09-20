<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/p00s6tbuj.css';
import '../../css/f/fv_cpccws.css';
import '../../css/n/n3b691blg.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="p00s6tbuj"/><path class="fv_cpccws"/><path class="n3b691blg"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:ksuite-kdrive-dark" /></template>
