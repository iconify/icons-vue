<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/mixnoqw4k.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="mixnoqw4k"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="roentgen:lattice-light-left-light-right" /></template>
