<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/rnjj2qbym.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="rnjj2qbym"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ri:contacts-line" /></template>
