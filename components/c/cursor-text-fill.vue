<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/lki1sk28e.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="lki1sk28e"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:cursor-text-fill" /></template>
