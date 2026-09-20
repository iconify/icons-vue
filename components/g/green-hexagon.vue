<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/b527d3b3t.css';
import '../../css/x/x1mdp195q.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":72,"height":72};
const content = `<path class="b527d3b3t"/><path class="x1mdp195q"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="openmoji:green-hexagon" /></template>
