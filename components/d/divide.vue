<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/dw2um-8au.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":40,"height":40};
const content = `<path class="dw2um-8au"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iwwa:divide" /></template>
