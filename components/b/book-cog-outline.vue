<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/g60a0jb9n.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="g60a0jb9n"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:book-cog-outline" /></template>
