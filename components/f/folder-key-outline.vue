<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/rhw5rlbpx.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="rhw5rlbpx"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:folder-key-outline" /></template>
