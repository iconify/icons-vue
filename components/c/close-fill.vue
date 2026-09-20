<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/ntohb8g-s.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ntohb8g-s"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="si:close-fill" /></template>
