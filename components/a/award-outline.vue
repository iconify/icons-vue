<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/pfco4ib6p.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="pfco4ib6p"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="flowbite:award-outline" /></template>
