<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/ffqr3tfcz.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ffqr3tfcz"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="feather:heart" /></template>
