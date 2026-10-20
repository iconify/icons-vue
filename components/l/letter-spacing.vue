<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/yhnx-jb6c.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="yhnx-jb6c"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lucide:letter-spacing" /></template>
