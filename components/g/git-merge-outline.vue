<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/ih8imdosu.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":15,"height":15};
const content = `<path class="ih8imdosu"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="teenyicons:git-merge-outline" /></template>
