<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/ji5cev1ps.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ji5cev1ps"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="flowbite:cloud-meatball-outline" /></template>
