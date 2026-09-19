<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/rre9if6yl.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":640,"height":640};
const content = `<path class="rre9if6yl"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fa7-brands:fonticons-fi" /></template>
