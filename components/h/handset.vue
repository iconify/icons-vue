<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/u9b_1cblb.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="u9b_1cblb"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="at-icons:handset" /></template>
