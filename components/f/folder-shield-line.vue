<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/a60lilr8h.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="a60lilr8h"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ri:folder-shield-line" /></template>
