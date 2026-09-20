<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/l8y4tcbiy.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="l8y4tcbiy"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="nonicons:java-16" /></template>
