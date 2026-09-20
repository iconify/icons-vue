<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/raslbftwc.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":15,"height":15};
const content = `<path class="raslbftwc"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pinhead:coffee-mug-and-saucer" /></template>
