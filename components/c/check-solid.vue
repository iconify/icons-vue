<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/fhy6a3bsq.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="fhy6a3bsq"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pixel:check-solid" /></template>
