<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/nzd6rhiup.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="nzd6rhiup"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:currency-dollar-2-fill" /></template>
