<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/nrj6p8qat.css';
import '../../css/g/gv_4pqnlw.css';
import '../../css/r/rus9pebka.css';
import '../../css/j/jhxi-trnl.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="gv_4pqnlw"/><circle class="rus9pebka"/><rect class="jhxi-trnl"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lucide:contact-round" /></template>
