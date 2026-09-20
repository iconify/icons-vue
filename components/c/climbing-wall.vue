<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/p7ij8m92l.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":15,"height":15};
const content = `<path class="p7ij8m92l"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pinhead:climbing-wall" /></template>
