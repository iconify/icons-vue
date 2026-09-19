<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/s6zob2bly.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":640,"height":640};
const content = `<path class="s6zob2bly"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fa7-brands:java" /></template>
