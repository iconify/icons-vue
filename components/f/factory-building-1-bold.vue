<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/d6hp64p8u.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="d6hp64p8u"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-ultimate:factory-building-1-bold" /></template>
