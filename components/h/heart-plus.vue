<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/oz5hput7f.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="oz5hput7f"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="hugeicons:heart-plus" /></template>
