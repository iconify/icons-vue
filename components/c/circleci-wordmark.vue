<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/h6a6m7bhx.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":128,"height":128};
const content = `<path class="h6a6m7bhx"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="devicon-plain:circleci-wordmark" /></template>
