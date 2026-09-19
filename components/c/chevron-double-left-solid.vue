<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/lpi2c7bge.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="lpi2c7bge"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="flowbite:chevron-double-left-solid" /></template>
