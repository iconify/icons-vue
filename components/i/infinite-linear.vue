<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/n708t0bcf.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="n708t0bcf"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:infinite-linear" /></template>
