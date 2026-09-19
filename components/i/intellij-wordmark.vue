<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/exq9hec0e.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":128,"height":128};
const content = `<path class="exq9hec0e"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="devicon-plain:intellij-wordmark" /></template>
