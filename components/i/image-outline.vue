<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/dtc0q9bxs.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":15,"height":15};
const content = `<path class="dtc0q9bxs"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="teenyicons:image-outline" /></template>
