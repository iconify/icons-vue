<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/eyf8j3bsu.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="eyf8j3bsu"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="flowbite:lock-outline" /></template>
