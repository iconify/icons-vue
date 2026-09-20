<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/b9_fmcj7v.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":15,"height":15};
const content = `<path class="b9_fmcj7v"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pinhead:arrow-left-from-tall-rectangle-outline" /></template>
