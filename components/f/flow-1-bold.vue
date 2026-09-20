<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/foz0jfb6z.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="foz0jfb6z"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-ultimate:flow-1-bold" /></template>
