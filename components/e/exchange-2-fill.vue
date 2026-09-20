<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/pc8h3-brf.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="pc8h3-brf"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ri:exchange-2-fill" /></template>
