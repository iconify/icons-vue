<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/dl5ybsbbl.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="dl5ybsbbl"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="raphael:feed" /></template>
