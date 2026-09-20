<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/p6torgwdu.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="p6torgwdu"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:alphabet-g-box" /></template>
