<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/ct_bdfr0m.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ct_bdfr0m"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ri:fire-fill" /></template>
