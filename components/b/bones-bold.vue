<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/fo3ldvyho.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="fo3ldvyho"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:bones-bold" /></template>
