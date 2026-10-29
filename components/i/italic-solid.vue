<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/ivikd782t.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ivikd782t"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="withicons:italic-solid" /></template>
