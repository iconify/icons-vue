<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/c2nysfb4v.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":22,"height":22};
const content = `<path class="c2nysfb4v"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="memory:castle" /></template>
