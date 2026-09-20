<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/g_-kcvb0v.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="g_-kcvb0v"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ri:hard-drive-fill" /></template>
