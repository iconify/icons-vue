<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/kkw265b-g.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":128,"height":128};
const content = `<path class="kkw265b-g"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="devicon-plain:angularjs-wordmark" /></template>
