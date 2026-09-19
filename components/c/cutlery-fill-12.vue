<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/ookrclnkg.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":12,"height":12};
const content = `<path class="ookrclnkg"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="garden:cutlery-fill-12" /></template>
