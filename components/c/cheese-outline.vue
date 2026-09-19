<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/izu-4o1ct.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="izu-4o1ct"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="flowbite:cheese-outline" /></template>
