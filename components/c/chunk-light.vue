<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/dmb9zzosy.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":65,"height":65,"left":33};
const content = `<path class="dmb9zzosy"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="thesvg-color:chunk-light" /></template>
