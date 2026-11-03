<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/yhrg1ac9g.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":128,"height":128};
const content = `<path class="yhrg1ac9g"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="devicon-plain:dialogflow" /></template>
