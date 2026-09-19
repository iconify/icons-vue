<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/or953jb6p.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="or953jb6p"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="boxicons:cursor-click-filled" /></template>
