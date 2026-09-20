<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/nrj6p8qat.css';
import '../../css/f/fntzryfta.css';
import '../../css/i/iw2xs4bqm.css';
import '../../css/g/gzjxlqbhq.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="fntzryfta"/><path class="iw2xs4bqm"/><path class="gzjxlqbhq"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lucide:calendar-sync" /></template>
