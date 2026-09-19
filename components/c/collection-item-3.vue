<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/b805xndzp.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":472,"height":480};
const content = `<path class="b805xndzp"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="zmdi:collection-item-3" /></template>
