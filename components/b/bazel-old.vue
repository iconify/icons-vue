<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/cz1vtzbsv.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":355,"height":512};
const content = `<path class="cz1vtzbsv"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="file-icons:bazel-old" /></template>
