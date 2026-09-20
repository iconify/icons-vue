<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/d718p-_-o.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="d718p-_-o"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ri:haze-line" /></template>
