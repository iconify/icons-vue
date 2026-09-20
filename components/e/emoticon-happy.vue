<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/akm6_1a0s.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="akm6_1a0s"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:emoticon-happy" /></template>
