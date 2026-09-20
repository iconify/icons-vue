<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/h01tyzbfu.css';
import '../../css/n/nl4j3gbuu.css';
import '../../css/f/fayk6ibbo.css';
import '../../css/z/z7h9dmbpz.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="h01tyzbfu"><path class="nl4j3gbuu"/><path class="fayk6ibbo"/><rect class="z7h9dmbpz"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mage:information-square" /></template>
