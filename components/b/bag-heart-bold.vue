<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/vt6bsdzhq.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="vt6bsdzhq"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:bag-heart-bold" /></template>
