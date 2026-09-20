<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/e0d37kbbh.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":15,"height":15};
const content = `<path class="e0d37kbbh"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="temaki:bicycle-structure" /></template>
