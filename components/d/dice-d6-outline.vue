<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/e5d4zmleu.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="e5d4zmleu"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:dice-d6-outline" /></template>
