<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/nrj6p8qat.css';
import '../../css/i/isv7l49qo.css';
import '../../css/v/va4yoc50j.css';
import '../../css/t/trsr16b4c.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="isv7l49qo"/><ellipse class="va4yoc50j"/><path class="trsr16b4c"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lucide:drum" /></template>
