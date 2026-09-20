<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/v4x2o6byr.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="v4x2o6byr"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="oui:folder-closed" /></template>
