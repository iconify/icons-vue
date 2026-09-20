<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/nrj6p8qat.css';
import '../../css/a/a6mwcibor.css';
import '../../css/u/uw8igebtn.css';
import '../../css/x/xg5g8jbtr.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="a6mwcibor"/><path class="uw8igebtn"/><path class="xg5g8jbtr"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="tabler:brand-discord" /></template>
