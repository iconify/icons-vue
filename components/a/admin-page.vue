<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/zzmgk0qpc.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="zzmgk0qpc"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="dashicons:admin-page" /></template>
