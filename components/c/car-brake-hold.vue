<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/zix2v434n.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="zix2v434n"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:car-brake-hold" /></template>
