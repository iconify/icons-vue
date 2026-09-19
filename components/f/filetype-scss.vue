<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/f3rypsbea.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="f3rypsbea"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="bi:filetype-scss" /></template>
