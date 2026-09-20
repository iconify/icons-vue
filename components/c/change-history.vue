<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/v0wndub2k.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="v0wndub2k"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:change-history" /></template>
