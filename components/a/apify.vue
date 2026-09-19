<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/ayg3j6s8f.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":128,"height":128};
const content = `<path class="ayg3j6s8f"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="devicon-plain:apify" /></template>
