<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/j2nzyh5rb.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="j2nzyh5rb"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:fuse-off" /></template>
