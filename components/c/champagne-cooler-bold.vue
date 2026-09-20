<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/lo5h1rzkj.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="lo5h1rzkj"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-ultimate:champagne-cooler-bold" /></template>
