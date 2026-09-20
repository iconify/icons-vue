<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/nhm6svbhf.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="nhm6svbhf"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:columns-3-fill" /></template>
