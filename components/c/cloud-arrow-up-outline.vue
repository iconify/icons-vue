<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/zo1euzr0p.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="zo1euzr0p"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="flowbite:cloud-arrow-up-outline" /></template>
