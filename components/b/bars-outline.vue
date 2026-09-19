<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/cfttagd8c.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="cfttagd8c"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="flowbite:bars-outline" /></template>
