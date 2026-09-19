<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/dyf1f2g-v.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":128,"height":128};
const content = `<path class="dyf1f2g-v"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="devicon-plain:awk-wordmark" /></template>
