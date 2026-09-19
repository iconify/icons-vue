<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/flen3tbdj.css';
import '../../css/w/wn1r12ziq.css';
import '../../css/s/shu3xdl9q.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="flen3tbdj"><path class="wn1r12ziq"/><circle class="shu3xdl9q"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="akar-icons:equal" /></template>
