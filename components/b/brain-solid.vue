<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/ccb9qpb9m.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ccb9qpb9m"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="withicons:brain-solid" /></template>
