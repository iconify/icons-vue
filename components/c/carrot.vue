<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/e6e890s2d.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":12,"height":12};
const content = `<path class="e6e890s2d"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="dinkie-icons:carrot" /></template>
