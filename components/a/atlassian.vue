<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/p3o3kbztd.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="p3o3kbztd"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="la:atlassian" /></template>
