<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/zcj8ggbve.css';
import '../../css/a/aynzu-bjt.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":222,"height":217};
const content = `<path class="zcj8ggbve"/><path class="aynzu-bjt"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="thesvg-color:justcall" /></template>
