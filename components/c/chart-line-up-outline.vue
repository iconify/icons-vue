<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/ubj1bvaep.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ubj1bvaep"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="flowbite:chart-line-up-outline" /></template>
