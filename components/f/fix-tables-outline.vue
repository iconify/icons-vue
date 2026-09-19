<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/m3aylzbdr.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="m3aylzbdr"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="flowbite:fix-tables-outline" /></template>
