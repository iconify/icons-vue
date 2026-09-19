<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/u7rn45-1q.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":128,"height":128};
const content = `<path class="u7rn45-1q"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="devicon-plain:frankenphp-wordmark" /></template>
