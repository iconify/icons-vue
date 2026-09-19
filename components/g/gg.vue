<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/oagrx1-ci.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":1920,"height":1344};
const content = `<path class="oagrx1-ci"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fa:gg" /></template>
