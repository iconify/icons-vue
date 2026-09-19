<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/r-2fky5wf.css';
import '../../css/u/ui9t6fbrk.css';
import '../../css/o/ov3lkhboq.css';
import '../../css/l/l9uwdzjst.css';
import '../../css/l/lomgru0ya.css';
import '../../css/x/xupt9bcnc.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="r-2fky5wf"/><rect class="ui9t6fbrk"/><rect class="ov3lkhboq"/><rect class="l9uwdzjst"/><rect class="lomgru0ya"/><rect class="xupt9bcnc"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="circum:barcode" /></template>
