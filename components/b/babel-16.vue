<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/h40kk1bvm.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path clip-rule="evenodd" class="h40kk1bvm"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="nonicons:babel-16" /></template>
