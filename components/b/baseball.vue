<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/dnx1jxbyw.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="dnx1jxbyw"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:baseball" /></template>
