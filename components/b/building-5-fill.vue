<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/xi4a8_62c.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="xi4a8_62c"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:building-5-fill" /></template>
