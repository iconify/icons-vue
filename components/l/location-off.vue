<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/j0wb7dbsj.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="j0wb7dbsj"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="guidance:location-off" /></template>
