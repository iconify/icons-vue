<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/tfz61wbip.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="tfz61wbip"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="flowbite:circle-pause-outline" /></template>
