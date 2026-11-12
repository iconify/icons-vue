<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/aewnve1os.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":128,"height":128};
const content = `<path class="aewnve1os"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="devicon-plain:databricks-wordmark" /></template>
