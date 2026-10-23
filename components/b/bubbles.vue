<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/ig5na-6tz.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ig5na-6tz"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="vadivam:bubbles" /></template>
