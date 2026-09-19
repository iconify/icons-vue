<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/igi-6tbii.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="igi-6tbii"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="flowbite:arrows-repeat-outline" /></template>
