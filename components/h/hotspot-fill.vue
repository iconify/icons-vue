<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/i7e5a7pja.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="i7e5a7pja"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ri:hotspot-fill" /></template>
