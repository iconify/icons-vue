<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/rux_79ovi.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="rux_79ovi"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="at-icons:fish" /></template>
