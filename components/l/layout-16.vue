<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/jlk56mgjt.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="jlk56mgjt"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="nonicons:layout-16" /></template>
