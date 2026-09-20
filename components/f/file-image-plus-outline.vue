<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/chq9vvbwh.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="chq9vvbwh"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:file-image-plus-outline" /></template>
