<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/ba5cak1-s.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ba5cak1-s"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:corn-off" /></template>
