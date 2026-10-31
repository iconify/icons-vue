<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/j40wsjfyj.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="j40wsjfyj"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="sidekickicons:headphones-slash-solid" /></template>
