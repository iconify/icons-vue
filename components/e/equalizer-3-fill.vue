<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/ahvhl-yox.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ahvhl-yox"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ri:equalizer-3-fill" /></template>
