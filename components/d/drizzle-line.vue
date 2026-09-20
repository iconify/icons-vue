<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/c_-5cwb9i.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="c_-5cwb9i"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ri:drizzle-line" /></template>
