<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/swk7trbne.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="swk7trbne"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="codicon:history" /></template>
