<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/cvi49bcnm.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":924.464,"height":1000};
const content = `<path class="cvi49bcnm"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="brandico:github-text" /></template>
