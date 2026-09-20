<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/oi1hetygf.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="oi1hetygf"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ri:hq-fill" /></template>
