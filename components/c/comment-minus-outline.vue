<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/bqxir0bwy.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="bqxir0bwy"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:comment-minus-outline" /></template>
