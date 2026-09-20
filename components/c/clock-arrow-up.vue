<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/nrj6p8qat.css';
import '../../css/r/rlyqeqb5c.css';
import '../../css/w/wtl4ombtk.css';
import '../../css/i/iz5phjbrv.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="rlyqeqb5c"/><path class="wtl4ombtk"/><path class="iz5phjbrv"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lucide:clock-arrow-up" /></template>
