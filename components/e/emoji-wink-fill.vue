<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/h_993vbsf.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="h_993vbsf"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="bi:emoji-wink-fill" /></template>
