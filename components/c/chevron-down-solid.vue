<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/aawx6do2i.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="aawx6do2i"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="flowbite:chevron-down-solid" /></template>
