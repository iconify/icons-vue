<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/maz51bb-c.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="maz51bb-c"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="eva:crop-outline" /></template>
