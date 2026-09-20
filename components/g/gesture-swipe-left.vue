<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/v_p_olule.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="v_p_olule"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:gesture-swipe-left" /></template>
