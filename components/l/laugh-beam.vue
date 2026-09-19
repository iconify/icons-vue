<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/tmts52bbz.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":640,"height":640};
const content = `<path class="tmts52bbz"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fa7-solid:laugh-beam" /></template>
