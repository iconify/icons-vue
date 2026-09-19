<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/qs2-cdbrd.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="qs2-cdbrd"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="heroicons:bars-2" /></template>
