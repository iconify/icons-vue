<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/ft5dv1b6b.css';
import '../../css/f/fxkgtbnra.css';
import '../../css/w/ww8n9zbdv.css';
import '../../css/l/lh9--2mlv.css';
import '../../css/e/epyi31bqc.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":1024,"height":1024};
const content = `<g class="ft5dv1b6b"><rect class="fxkgtbnra"/><circle class="ww8n9zbdv"/><circle class="lh9--2mlv"/><circle class="epyi31bqc"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="thesvg-color:daisyui" /></template>
