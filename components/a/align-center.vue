<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/g4m27vkmy.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="g4m27vkmy"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uim:align-center" /></template>
