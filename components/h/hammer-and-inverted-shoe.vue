<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/d03a88bzw.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":15,"height":15};
const content = `<path class="d03a88bzw"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pinhead:hammer-and-inverted-shoe" /></template>
