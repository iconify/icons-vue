<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/dvsnbwb2g.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":128,"height":128};
const content = `<path class="dvsnbwb2g"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="devicon-plain:azuredevops" /></template>
