<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/b0rxu6dnz.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="b0rxu6dnz"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="roentgen:greek-cross" /></template>
