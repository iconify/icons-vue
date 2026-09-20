<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/h495ombwo.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="h495ombwo"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:comment-eye" /></template>
