<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/wciugabom.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="wciugabom"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:laptop-3-outline" /></template>
