<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/nucqz5bfy.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="nucqz5bfy"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:add-circle-outline" /></template>
