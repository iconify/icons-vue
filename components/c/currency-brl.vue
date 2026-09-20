<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/jpl5qy6cx.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="jpl5qy6cx"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:currency-brl" /></template>
