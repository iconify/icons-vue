<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/fisikzwzx.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="fisikzwzx"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mynaui:letter-g-waves-solid" /></template>
