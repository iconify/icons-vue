<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/v9j6bob4g.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="v9j6bob4g"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="dashicons:backup" /></template>
