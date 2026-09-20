<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/denthcbya.css';
import '../../css/r/roadlpwdh.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":72,"height":72};
const content = `<path class="denthcbya"/><path class="roadlpwdh"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="openmoji:cactus" /></template>
