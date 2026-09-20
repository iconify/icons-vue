<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/gpy6qzbjf.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":15,"height":15};
const content = `<path class="gpy6qzbjf"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="teenyicons:game-controller-retro-outline" /></template>
