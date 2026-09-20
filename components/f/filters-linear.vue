<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/h29j--52h.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="h29j--52h"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:filters-linear" /></template>
