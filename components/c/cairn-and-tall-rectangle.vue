<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/y5stnbb3e.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":15,"height":15};
const content = `<path class="y5stnbb3e"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pinhead:cairn-and-tall-rectangle" /></template>
