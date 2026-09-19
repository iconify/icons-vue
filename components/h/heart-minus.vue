<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/qkx9uxboa.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="qkx9uxboa"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="hugeicons:heart-minus" /></template>
