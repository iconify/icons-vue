<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/z_p8a8bro.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="z_p8a8bro"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:filter-menu-outline" /></template>
