<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/oru5bnb6j.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="oru5bnb6j"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="majesticons:analytics-delete-line" /></template>
