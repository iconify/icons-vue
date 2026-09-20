<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/bbkwmk22y.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="bbkwmk22y"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:home-floor-b" /></template>
