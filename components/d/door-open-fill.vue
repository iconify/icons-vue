<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/hjsh7bb3t.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="hjsh7bb3t"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ri:door-open-fill" /></template>
