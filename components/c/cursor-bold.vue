<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/y_88jdbml.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="y_88jdbml"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:cursor-bold" /></template>
