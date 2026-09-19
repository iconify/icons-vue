<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/w1her1mbe.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="w1her1mbe"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="bx:bxs-message-add" /></template>
