<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/rjjw5bber.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":256,"height":488};
const content = `<path class="rjjw5bber"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ps:github" /></template>
