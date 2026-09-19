<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/sg9nnwstw.css';
import '../../css/u/uz_ojxb6y.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="sg9nnwstw"/><path class="uz_ojxb6y"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ion:flame-outline" /></template>
