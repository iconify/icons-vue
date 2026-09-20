<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/s68f012ke.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="s68f012ke"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:house-edit-outline" /></template>
