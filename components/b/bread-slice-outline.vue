<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/mhg9dj5mg.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="mhg9dj5mg"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:bread-slice-outline" /></template>
