<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/tb25vubxe.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="tb25vubxe"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:credit-card-check" /></template>
