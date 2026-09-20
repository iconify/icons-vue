<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/d9-c96but.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":15,"height":15};
const content = `<path class="d9-c96but"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pinhead:cat-sitting" /></template>
