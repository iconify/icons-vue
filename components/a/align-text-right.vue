<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/t-qk5zavh.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":25,"height":24};
const content = `<path class="t-qk5zavh"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lineicons:align-text-right" /></template>
