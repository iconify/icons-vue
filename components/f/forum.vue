<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/inr2iybus.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="inr2iybus"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi-light:forum" /></template>
