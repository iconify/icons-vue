<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/d0bqak86z.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="d0bqak86z"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:forward-outline" /></template>
