<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/wg5ex23xf.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="wg5ex23xf"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="garden:eye-hide-stroke-16" /></template>
