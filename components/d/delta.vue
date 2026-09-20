<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/vyg-aubic.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":40,"height":40};
const content = `<path class="vyg-aubic"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iwwa:delta" /></template>
