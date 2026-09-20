<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/f9c8rcbdc.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path clip-rule="evenodd" class="f9c8rcbdc"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="qlementine-icons:close-16" /></template>
