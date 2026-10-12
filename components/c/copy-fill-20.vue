<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/d5o0g-62r.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="d5o0g-62r"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="garden:copy-fill-20" /></template>
