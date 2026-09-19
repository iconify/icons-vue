<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/g-agxvvjv.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="g-agxvvjv"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoir:layout-right" /></template>
