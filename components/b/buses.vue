<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/cwgzr4b-a.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="cwgzr4b-a"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="roentgen:buses" /></template>
