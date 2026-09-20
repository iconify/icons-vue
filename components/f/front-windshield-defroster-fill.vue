<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/dvz8k-fun.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="dvz8k-fun"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:front-windshield-defroster-fill" /></template>
