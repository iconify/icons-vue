<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/rdngab7on.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":128,"height":128};
const content = `<path class="rdngab7on"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="devicon-plain:android-wordmark" /></template>
