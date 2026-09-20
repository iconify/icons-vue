<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/oiozi-bue.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":15,"height":15};
const content = `<path class="oiozi-bue"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pinhead:cairn-and-two-tall-rectangles-top-right" /></template>
