<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/hw5xwqyzi.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="hw5xwqyzi"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="qlementine-icons:cube-16" /></template>
