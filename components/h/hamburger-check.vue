<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/m76g-hbcz.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="m76g-hbcz"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:hamburger-check" /></template>
