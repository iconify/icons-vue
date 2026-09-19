<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/yfky60b3j.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="yfky60b3j"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="flowbite:cell-attributes-outline" /></template>
