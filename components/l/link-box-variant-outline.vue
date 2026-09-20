<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/k5x223bnd.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="k5x223bnd"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:link-box-variant-outline" /></template>
