<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/cgx4t6bka.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="cgx4t6bka"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="vadivam:bean-off" /></template>
