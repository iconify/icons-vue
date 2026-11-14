<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/l8w5gd35u.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="l8w5gd35u"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="hugeicons:ai-content-generator-01" /></template>
