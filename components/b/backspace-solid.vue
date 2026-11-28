<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/z0my4wugx.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="z0my4wugx"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconaut:backspace-solid" /></template>
