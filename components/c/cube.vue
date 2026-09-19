<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/m16dw2hxd.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="m16dw2hxd"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="heroicons:cube" /></template>
