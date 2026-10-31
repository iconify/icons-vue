<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/j_be7nb9d.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="j_be7nb9d"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:coins-fill-round" /></template>
