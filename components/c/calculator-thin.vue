<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/h01tyzbfu.css';
import '../../css/g/gd8dsqbqp.css';
import '../../css/c/craj1zw4d.css';
import '../../css/g/gqixgnb9o.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="h01tyzbfu"><path class="gd8dsqbqp"/><path class="craj1zw4d"/><path class="gqixgnb9o"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconamoon:calculator-thin" /></template>
