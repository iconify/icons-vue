<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/c8mb6096f.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="c8mb6096f"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:clock-4" /></template>
