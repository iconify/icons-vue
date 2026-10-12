<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/l-c__p3wy.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="l-c__p3wy"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lucide:handle-bottom-right" /></template>
