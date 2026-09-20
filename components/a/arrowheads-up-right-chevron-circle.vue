<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/zewnb2-ur.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path clip-rule="evenodd" class="zewnb2-ur"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-block:arrowheads-up-right-chevron-circle" /></template>
