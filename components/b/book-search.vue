<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/nrj6p8qat.css';
import '../../css/m/mw7g6hbqn.css';
import '../../css/i/i5ctgrq3h.css';
import '../../css/e/e6kbp_ktm.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="mw7g6hbqn"/><path class="i5ctgrq3h"/><circle class="e6kbp_ktm"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lucide:book-search" /></template>
