<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/dauqcps4o.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="dauqcps4o"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="flowbite:font-highlight-outline" /></template>
