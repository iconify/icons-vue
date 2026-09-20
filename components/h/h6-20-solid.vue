<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/h8gfwgb1n.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="h8gfwgb1n"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="sidekickicons:h6-20-solid" /></template>
