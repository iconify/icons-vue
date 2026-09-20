<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/w8ilc_b3v.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="w8ilc_b3v"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:close-outline" /></template>
