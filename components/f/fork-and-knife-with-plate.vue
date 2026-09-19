<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/ft5dv1b6b.css';
import '../../css/m/mmao8sg7p.css';
import '../../css/u/udi1b0fzv.css';
import '../../css/o/oyp3k4snw.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<g class="ft5dv1b6b"><path class="mmao8sg7p"/><path class="udi1b0fzv"/><path class="oyp3k4snw"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent-emoji-flat:fork-and-knife-with-plate" /></template>
