<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/hal7cto6v.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="hal7cto6v"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="roentgen:charging-station" /></template>
