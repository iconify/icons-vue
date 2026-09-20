<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/idpmgebvh.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="idpmgebvh"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lucide-lab:barber-pole" /></template>
