<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/fx61_ej9h.css';
import '../../css/e/eyyhcy0xu.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":72,"height":72};
const content = `<path class="fx61_ej9h"/><path class="eyyhcy0xu"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="openmoji:left-arrow-curving-right" /></template>
