<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/ft5dv1b6b.css';
import '../../css/m/mokpvmbch.css';
import '../../css/k/ki6jfibdu.css';
import '../../css/k/kt8eunb4u.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":80,"height":80};
const content = `<g class="ft5dv1b6b"><path clip-rule="evenodd" class="mokpvmbch"/><path class="ki6jfibdu"/><path class="kt8eunb4u"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="glyphs:campfire-bold" /></template>
