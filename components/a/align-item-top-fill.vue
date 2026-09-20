<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/ihq9t13ew.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ihq9t13ew"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ri:align-item-top-fill" /></template>
