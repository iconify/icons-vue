<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/a7q-667gm.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="a7q-667gm"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:floor-light-dual" /></template>
