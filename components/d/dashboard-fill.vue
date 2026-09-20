<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/m802_1bgx.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="m802_1bgx"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mage:dashboard-fill" /></template>
