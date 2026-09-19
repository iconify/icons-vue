<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/x-s9xac3q.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="x-s9xac3q"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="gridicons:align-image-left" /></template>
