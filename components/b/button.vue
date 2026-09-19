<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/i_ubzn6on.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="i_ubzn6on"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="cbi:button" /></template>
