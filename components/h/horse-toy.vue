<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/nrj6p8qat.css';
import '../../css/i/ie1lktb8t.css';
import '../../css/f/fwf3hft6m.css';
import '../../css/d/dph3etpje.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="ie1lktb8t"/><path class="fwf3hft6m"/><path class="dph3etpje"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="tabler:horse-toy" /></template>
