<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/jx0p4fbya.css';
import '../../css/m/mmj0dutfl.css';
import '../../css/c/c_cjlv91j.css';
import '../../css/a/aedg6zbbn.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="jx0p4fbya"><path class="mmj0dutfl"/><path class="c_cjlv91j"/><path class="aedg6zbbn"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="hugeicons:image-composition" /></template>
