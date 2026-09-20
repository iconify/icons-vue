<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/du4w56b8f.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":15,"height":15};
const content = `<path class="du4w56b8f"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="teenyicons:database-outline" /></template>
