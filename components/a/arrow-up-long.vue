<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/n7xx_wbpu.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="n7xx_wbpu"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="meteor-icons:arrow-up-long" /></template>
