<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/nan55u7bm.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":640,"height":640};
const content = `<path class="nan55u7bm"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fa7-solid:bone" /></template>
