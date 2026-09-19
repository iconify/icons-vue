<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/v5hhzc2pb.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":42,"height":42};
const content = `<path class="v5hhzc2pb"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="topcoat:image" /></template>
