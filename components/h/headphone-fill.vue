<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/ix7mdhbky.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ix7mdhbky"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ri:headphone-fill" /></template>
