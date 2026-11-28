<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/lcm84xffx.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="lcm84xffx"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconaut:beer-solid" /></template>
