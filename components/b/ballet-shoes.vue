<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/c6a0qnbks.css';
import '../../css/k/k2rhzeb7g.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":72,"height":72};
const content = `<path class="c6a0qnbks"/><path class="k2rhzeb7g"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="openmoji:ballet-shoes" /></template>
