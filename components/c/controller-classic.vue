<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/en2kx7bmo.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="en2kx7bmo"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:controller-classic" /></template>
