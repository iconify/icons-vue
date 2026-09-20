<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/mav9q8bay.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="mav9q8bay"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="majesticons:add-row" /></template>
