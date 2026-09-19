<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/oh__mfoxn.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="oh__mfoxn"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="at-icons:checkerboard" /></template>
