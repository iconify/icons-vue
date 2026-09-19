<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/syg8jbb6q.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="syg8jbb6q"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="hugeicons:drag-drop" /></template>
