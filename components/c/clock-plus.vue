<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/eow-9nb1b.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="eow-9nb1b"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:clock-plus" /></template>
