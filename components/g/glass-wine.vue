<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/wmemcjbea.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="wmemcjbea"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:glass-wine" /></template>
