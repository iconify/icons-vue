<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/f8t1gyelg.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="f8t1gyelg"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:database-arrow-down-outline" /></template>
