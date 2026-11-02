<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/e5dcb7b6j.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="e5dcb7b6j"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:circle-arrow-out-down-right-fill" /></template>
