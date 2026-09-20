<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/x85j1tb5o.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="x85j1tb5o"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:doctor" /></template>
