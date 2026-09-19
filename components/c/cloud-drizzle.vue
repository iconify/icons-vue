<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/dwxv6dbcz.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="dwxv6dbcz"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="hugeicons:cloud-drizzle" /></template>
