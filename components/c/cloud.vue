<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/dgriz_p_e.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="dgriz_p_e"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="gridicons:cloud" /></template>
