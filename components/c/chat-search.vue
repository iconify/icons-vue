<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/flen3tbdj.css';
import '../../css/l/lfxfqtu8m.css';
import '../../css/a/aqcas2i6m.css';
import '../../css/g/ghvo08b3e.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="flen3tbdj"><path class="lfxfqtu8m"/><circle class="aqcas2i6m"/><path class="ghvo08b3e"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lets-icons:chat-search" /></template>
