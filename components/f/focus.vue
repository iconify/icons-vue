<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/y690xsbid.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="y690xsbid"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="hugeicons:focus" /></template>
