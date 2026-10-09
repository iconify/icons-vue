<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/r4bjo-bjt.css';
import '../../css/v/v4ji3vb6c.css';
import '../../css/g/gqvbnmbwy.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="r4bjo-bjt"/><path class="v4ji3vb6c"/><path class="gqvbnmbwy"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:flange-20" /></template>
