<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/blbxstv4s.css';
import '../../css/y/y-zi9_bzo.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":72,"height":72};
const content = `<path class="blbxstv4s"/><path class="y-zi9_bzo"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="openmoji:large-orange-diamond" /></template>
