<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/fvc0dx3lz.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="fvc0dx3lz"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="akar-icons:arrow-up-left" /></template>
