<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/f1wdc4nuw.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="f1wdc4nuw"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:event-time" /></template>
