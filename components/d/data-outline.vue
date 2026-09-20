<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/oobsdcc_i.css';
import '../../css/n/n1mjunbsu.css';
import '../../css/f/flen3tbdj.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<defs><path id="SVGg38j6bxh" class="oobsdcc_i"/></defs><mask id="SVGgNbYfdiO" class="n1mjunbsu"><use href="#SVGg38j6bxh"/></mask><use href="#SVGg38j6bxh" mask="url(#SVGgNbYfdiO)" class="flen3tbdj"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lsicon:data-outline" /></template>
