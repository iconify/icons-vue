<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/pzn-cmbye.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":128,"height":128};
const content = `<path class="pzn-cmbye"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="devicon:coffeescript-wordmark" /></template>
