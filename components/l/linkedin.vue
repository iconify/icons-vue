<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/io96o8bux.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":42,"height":42};
const content = `<path class="io96o8bux"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="topcoat:linkedin" /></template>
