<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/f8f0kfb1z.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="f8f0kfb1z"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="vadivam:battery-low" /></template>
