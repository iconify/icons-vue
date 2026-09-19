<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/yg_0y-dzp.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="yg_0y-dzp"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="at-icons:feather" /></template>
