<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/j-2gqjb5z.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="j-2gqjb5z"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fa6-solid:binoculars" /></template>
