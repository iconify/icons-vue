<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/g7f_3dbco.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="g7f_3dbco"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:chat-square-bold" /></template>
