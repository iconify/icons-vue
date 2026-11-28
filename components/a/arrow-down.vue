<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/hav6w5euk.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="hav6w5euk"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="noviair-light:arrow-down" /></template>
