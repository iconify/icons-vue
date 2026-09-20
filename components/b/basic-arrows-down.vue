<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/zdvbgl_hv.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="zdvbgl_hv"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-block:basic-arrows-down" /></template>
