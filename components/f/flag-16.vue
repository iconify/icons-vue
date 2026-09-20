<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/fdijvhc5p.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="fdijvhc5p"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="octicon:flag-16" /></template>
