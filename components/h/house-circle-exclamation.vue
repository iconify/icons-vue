<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/r2gh_abbu.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":640,"height":640};
const content = `<path class="r2gh_abbu"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fa7-solid:house-circle-exclamation" /></template>
