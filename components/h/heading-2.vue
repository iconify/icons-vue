<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/irgq9rb1q.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="irgq9rb1q"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lucide:heading-2" /></template>
