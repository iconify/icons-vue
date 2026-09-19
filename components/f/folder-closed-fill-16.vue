<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/v58lonbsl.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="v58lonbsl"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="garden:folder-closed-fill-16" /></template>
