<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/iw-4-8pcl.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":15,"height":15};
const content = `<path class="iw-4-8pcl"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pinhead:kick-scooter" /></template>
