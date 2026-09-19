<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/ribmjwslf.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ribmjwslf"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="boxicons:hourglass-filled" /></template>
