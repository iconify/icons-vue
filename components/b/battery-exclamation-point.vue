<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/crr0vzbga.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="crr0vzbga"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lucide:battery-exclamation-point" /></template>
