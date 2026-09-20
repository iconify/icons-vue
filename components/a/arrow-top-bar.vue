<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/f07w5edil.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="f07w5edil"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="tabler:arrow-top-bar" /></template>
