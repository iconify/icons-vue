<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/duu6_4t6e.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="duu6_4t6e"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:arrow-bottom-right-thin" /></template>
