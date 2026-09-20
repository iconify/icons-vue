<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/ofn0e2wdh.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":12,"height":16};
const content = `<path class="ofn0e2wdh"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="octicon:list-unordered" /></template>
