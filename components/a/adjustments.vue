<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/d2jmuwhpv.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="d2jmuwhpv"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="humbleicons:adjustments" /></template>
