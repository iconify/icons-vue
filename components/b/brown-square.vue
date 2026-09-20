<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/f_a9inbrs.css';
import '../../css/t/tbzab391z.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":72,"height":72};
const content = `<path class="f_a9inbrs"/><path class="tbzab391z"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="openmoji:brown-square" /></template>
