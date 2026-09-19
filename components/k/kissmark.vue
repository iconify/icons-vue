<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/p19pb4brm.css';
import '../../css/b/bm_a0o4dd.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":72,"height":72};
const content = `<path class="p19pb4brm"/><path class="bm_a0o4dd"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fxemoji:kissmark" /></template>
