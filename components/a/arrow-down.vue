<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/ufww38b4l.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":40,"height":40};
const content = `<path class="ufww38b4l"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iwwa:arrow-down" /></template>
