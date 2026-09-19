<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/vek-gjbcu.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="vek-gjbcu"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="griddy-icons:battery-vertical-very-low" /></template>
