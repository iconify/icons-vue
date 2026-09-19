<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/edqny3bwh.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="edqny3bwh"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="at-icons:fog" /></template>
