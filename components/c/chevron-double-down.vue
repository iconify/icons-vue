<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/ysymgubea.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ysymgubea"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:chevron-double-down" /></template>
