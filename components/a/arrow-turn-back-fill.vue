<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/g5uhekmkh.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="g5uhekmkh"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ri:arrow-turn-back-fill" /></template>
