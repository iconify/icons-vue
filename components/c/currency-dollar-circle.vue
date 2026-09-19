<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/jm48-6mzu.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="jm48-6mzu"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="humbleicons:currency-dollar-circle" /></template>
