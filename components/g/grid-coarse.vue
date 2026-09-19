<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/eclwhcc2y.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="eclwhcc2y"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="at-icons:grid-coarse" /></template>
