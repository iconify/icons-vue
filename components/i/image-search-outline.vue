<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/hj6o4wafj.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="hj6o4wafj"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:image-search-outline" /></template>
