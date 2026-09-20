<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/w1n2s360d.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="w1n2s360d"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="simple-icons:hp" /></template>
