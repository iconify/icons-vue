<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/orr3tv0kz.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="orr3tv0kz"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconaut:bus-double-decker-solid" /></template>
