<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/t9uu54b7m.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="t9uu54b7m"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:add-thick" /></template>
