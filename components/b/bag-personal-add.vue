<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/slom_xddu.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="slom_xddu"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:bag-personal-add" /></template>
