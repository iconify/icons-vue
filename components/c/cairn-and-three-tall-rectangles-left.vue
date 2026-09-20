<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/yksgd-bkd.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":15,"height":15};
const content = `<path class="yksgd-bkd"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pinhead:cairn-and-three-tall-rectangles-left" /></template>
