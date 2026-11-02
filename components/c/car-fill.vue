<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/fb-1fbb5v.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="fb-1fbb5v"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:car-fill" /></template>
