<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/i-g5z-w8l.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="i-g5z-w8l"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="bx:bxs-message-alt-edit" /></template>
