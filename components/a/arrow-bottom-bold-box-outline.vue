<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/j-ehlsbuj.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="j-ehlsbuj"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:arrow-bottom-bold-box-outline" /></template>
