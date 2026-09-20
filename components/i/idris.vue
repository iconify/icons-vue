<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/v9xtyybbm.css';
import '../../css/a/alxwr1l7c.css';
import '../../css/x/xn7sace2l.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":200,"height":200};
const content = `<g class="v9xtyybbm"><path class="alxwr1l7c"/><path class="xn7sace2l"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-icon-theme:idris" /></template>
