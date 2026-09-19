<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/bq8j2vbxj.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":128,"height":128};
const content = `<path class="bq8j2vbxj"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="devicon-plain:goland-wordmark" /></template>
