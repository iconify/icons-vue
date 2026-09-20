<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/dy5q6bchh.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="dy5q6bchh"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:letter-bold" /></template>
