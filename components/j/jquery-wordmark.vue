<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/vy1qvyszu.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":128,"height":128};
const content = `<path class="vy1qvyszu"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="devicon-plain:jquery-wordmark" /></template>
