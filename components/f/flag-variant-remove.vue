<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/qpoc7h0yx.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="qpoc7h0yx"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:flag-variant-remove" /></template>
