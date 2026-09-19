<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/dz-b3xwif.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":128,"height":128};
const content = `<path class="dz-b3xwif"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="devicon-plain:gitea-wordmark" /></template>
