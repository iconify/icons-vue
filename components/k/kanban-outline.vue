<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/z_s7jsbvo.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":15,"height":15};
const content = `<path class="z_s7jsbvo"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="teenyicons:kanban-outline" /></template>
