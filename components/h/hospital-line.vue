<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/hqfj0_b4p.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="hqfj0_b4p"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="si:hospital-line" /></template>
