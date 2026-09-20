<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/exlscdc0w.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="exlscdc0w"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:cash-marker" /></template>
