<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/n6uyw0bfz.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="n6uyw0bfz"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="qlementine-icons:link-break-16" /></template>
