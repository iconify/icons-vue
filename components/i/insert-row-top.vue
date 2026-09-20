<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/wphz0abhz.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="wphz0abhz"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ri:insert-row-top" /></template>
