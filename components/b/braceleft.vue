<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/bb88lbest.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":289,"height":960};
const content = `<path class="bb88lbest"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ls:braceleft" /></template>
