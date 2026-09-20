<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/hs237eb8l.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="hs237eb8l"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="rivet-icons:home-solid" /></template>
