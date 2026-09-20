<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/zmph2sbez.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="zmph2sbez"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="qlementine-icons:guitar-jackson-16" /></template>
