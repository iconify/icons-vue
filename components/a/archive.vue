<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/w4xh7-bfx.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="w4xh7-bfx"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="heroicons-outline:archive" /></template>
