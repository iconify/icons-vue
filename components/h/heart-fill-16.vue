<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/jtgukcb8s.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="jtgukcb8s"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="octicon:heart-fill-16" /></template>
