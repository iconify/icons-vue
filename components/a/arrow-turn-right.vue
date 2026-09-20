<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/r3jglccvf.css';
import '../../css/c/cuikm_bqp.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":72,"height":72};
const content = `<path class="r3jglccvf"/><path class="cuikm_bqp"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="openmoji:arrow-turn-right" /></template>
