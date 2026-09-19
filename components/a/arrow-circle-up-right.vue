<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/vlt5bcb8g.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="vlt5bcb8g"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="griddy-icons:arrow-circle-up-right" /></template>
