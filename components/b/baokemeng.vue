<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/y3dpzbtra.css';
import '../../css/r/ry3fse1zo.css';
import '../../css/u/ul1worher.css';
import '../../css/l/llqfild5y.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<g class="y3dpzbtra"><path class="ry3fse1zo"/><path class="ul1worher"/><path class="llqfild5y"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="icon-park-solid:baokemeng" /></template>
