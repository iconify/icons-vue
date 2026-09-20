<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/oxnmjyt7u.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="oxnmjyt7u"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:live-location-fill" /></template>
