<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/zmhv16-fi.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="zmhv16-fi"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="dashicons:archive" /></template>
