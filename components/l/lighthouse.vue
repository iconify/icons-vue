<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/wourn01uj.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":15,"height":15};
const content = `<path class="wourn01uj"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="maki:lighthouse" /></template>
