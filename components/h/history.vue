<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/yv064jg5f.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="yv064jg5f"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="humbleicons:history" /></template>
