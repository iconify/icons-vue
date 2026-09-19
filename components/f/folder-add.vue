<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/bxng2-aly.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":100,"height":100};
const content = `<path class="bxng2-aly"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="foundation:folder-add" /></template>
