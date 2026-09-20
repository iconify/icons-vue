<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/vx0j4pwwu.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="vx0j4pwwu"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="tabler:bubble-minus" /></template>
