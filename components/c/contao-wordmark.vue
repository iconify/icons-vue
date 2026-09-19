<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/d0b6c_1tz.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":128,"height":128};
const content = `<path class="d0b6c_1tz"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="devicon:contao-wordmark" /></template>
