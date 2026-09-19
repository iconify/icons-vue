<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/fb8vuhygn.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="fb8vuhygn"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="hugeicons:add-invoice" /></template>
