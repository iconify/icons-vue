<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/f0g0kyhvw.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="f0g0kyhvw"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="bx:bxl-vk" /></template>
