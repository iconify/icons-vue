<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/e-qa1pbbz.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":1024,"height":1024};
const content = `<path class="e-qa1pbbz"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="simple-line-icons:film" /></template>
