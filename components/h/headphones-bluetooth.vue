<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/oro_-ac7a.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="oro_-ac7a"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:headphones-bluetooth" /></template>
