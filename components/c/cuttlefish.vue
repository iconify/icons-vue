<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/j1u7nbcba.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":640,"height":640};
const content = `<path class="j1u7nbcba"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fa7-brands:cuttlefish" /></template>
