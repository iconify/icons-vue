<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/j0m7m2btz.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="j0m7m2btz"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fa6-solid:bowl-food" /></template>
