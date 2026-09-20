<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/nrj6p8qat.css';
import '../../css/a/avoltjbjo.css';
import '../../css/h/h_tsn8bxt.css';
import '../../css/l/lv5w9wbqr.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><rect class="avoltjbjo"/><circle class="h_tsn8bxt"/><path class="lv5w9wbqr"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lucide:banknote" /></template>
