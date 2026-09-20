<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/kt_0gmpie.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="kt_0gmpie"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:book-sync" /></template>
