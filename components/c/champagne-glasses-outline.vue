<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/tf603ubza.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="tf603ubza"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="flowbite:champagne-glasses-outline" /></template>
