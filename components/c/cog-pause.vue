<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/pez1t_b8y.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="pez1t_b8y"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:cog-pause" /></template>
