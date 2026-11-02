<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/dal0b0eku.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="dal0b0eku"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:circle-fading-plus-fill" /></template>
