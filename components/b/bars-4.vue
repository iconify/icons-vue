<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/b3d02k97u.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="b3d02k97u"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="heroicons:bars-4" /></template>
