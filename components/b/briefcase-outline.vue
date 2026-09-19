<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/n1lsf0bnc.css';
import '../../css/h/hmhv31bxt.css';
import '../../css/s/slw3rea1g.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="briefcase-outline"><g class="Vector n1lsf0bnc" clip-rule="evenodd"><path class="hmhv31bxt"/><path class="slw3rea1g"/></g></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="cuida:briefcase-outline" /></template>
