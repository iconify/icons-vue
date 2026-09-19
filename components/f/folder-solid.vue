<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/dk1y5c0sj.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="dk1y5c0sj"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="basil:folder-solid" /></template>
