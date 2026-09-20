<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/s9lgcu2_p.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="s9lgcu2_p"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ri:home-2-fill" /></template>
