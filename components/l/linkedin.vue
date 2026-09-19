<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/kogk3ac4g.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":464,"height":480};
const content = `<path class="kogk3ac4g"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ps:linkedin" /></template>
