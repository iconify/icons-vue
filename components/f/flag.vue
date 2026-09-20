<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/q5m4sly5u.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="q5m4sly5u"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="rivet-icons:flag" /></template>
