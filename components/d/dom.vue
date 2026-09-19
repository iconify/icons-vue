<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/v7ithy0ty.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="v7ithy0ty"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="file-icons:dom" /></template>
