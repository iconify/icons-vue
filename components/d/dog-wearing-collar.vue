<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/u12cutb2e.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":15,"height":15};
const content = `<path class="u12cutb2e"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pinhead:dog-wearing-collar" /></template>
