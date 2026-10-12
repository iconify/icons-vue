<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/uyy55sbjn.css';
import '../../css/p/pksro9bgq.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="uyy55sbjn"/><path class="pksro9bgq"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="garden:accessibility-stroke-20" /></template>
