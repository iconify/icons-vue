<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/o7eiit0ys.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="o7eiit0ys"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:comment-outline" /></template>
