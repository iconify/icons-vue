<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/sregglbhf.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="sregglbhf"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="eva:battery-fill" /></template>
