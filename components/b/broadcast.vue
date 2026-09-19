<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/l8zqmhn6z.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="l8zqmhn6z"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="bi:broadcast" /></template>
