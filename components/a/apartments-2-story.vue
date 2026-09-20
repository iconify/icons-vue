<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/pvc994vvl.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="pvc994vvl"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="roentgen:apartments-2-story" /></template>
