<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/dep2gs26u.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="dep2gs26u"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="noviair:arrow-big-up" /></template>
