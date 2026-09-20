<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/f1r3n6bhi.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":15,"height":15};
const content = `<path class="f1r3n6bhi"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pinhead:campsite-on-platform" /></template>
