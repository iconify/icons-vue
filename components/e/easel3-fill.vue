<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/az63m7b8s.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="az63m7b8s"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="bi:easel3-fill" /></template>
