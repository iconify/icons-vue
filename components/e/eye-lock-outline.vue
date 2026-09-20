<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/o5zr_9r_s.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="o5zr_9r_s"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:eye-lock-outline" /></template>
