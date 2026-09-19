<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/ix9b12bwm.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ix9b12bwm"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoir:ease-in" /></template>
