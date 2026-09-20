<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/nyh081gqz.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="nyh081gqz"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:directions-2-fill" /></template>
