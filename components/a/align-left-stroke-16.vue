<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/b0gwnbb2e.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="b0gwnbb2e"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="garden:align-left-stroke-16" /></template>
