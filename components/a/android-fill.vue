<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/x6qilob1z.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="x6qilob1z"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ri:android-fill" /></template>
