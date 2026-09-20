<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/zkz42dmyd.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="zkz42dmyd"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="token:bgb" /></template>
