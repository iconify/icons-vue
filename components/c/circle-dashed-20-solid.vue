<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/glwy-gbnm.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="glwy-gbnm"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="sidekickicons:circle-dashed-20-solid" /></template>
