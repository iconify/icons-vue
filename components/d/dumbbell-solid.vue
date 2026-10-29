<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/le-25ab2z.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="le-25ab2z"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="withicons:dumbbell-solid" /></template>
