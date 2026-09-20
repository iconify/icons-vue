<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/ixh9d53ff.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":6,"height":16};
const content = `<path class="ixh9d53ff"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="octicon:italic" /></template>
