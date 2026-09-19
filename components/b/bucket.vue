<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/bi12bsetm.css';
import '../../css/c/c787b-zxi.css';
import '../../css/b/bxutvf4dz.css';
import '../../css/v/v62_33uqe.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":17,"height":16};
const content = `<g class="bi12bsetm"><path class="c787b-zxi"/><path class="bxutvf4dz"/><path class="v62_33uqe"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="si-glyph:bucket" /></template>
