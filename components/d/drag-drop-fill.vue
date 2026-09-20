<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/ia27gz4hm.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ia27gz4hm"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ri:drag-drop-fill" /></template>
