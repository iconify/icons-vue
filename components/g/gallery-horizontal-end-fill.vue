<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/rcx5dkeqi.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="rcx5dkeqi"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:gallery-horizontal-end-fill" /></template>
