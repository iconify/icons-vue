<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/mrkcwcg6y.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="mrkcwcg6y"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="struq:chevron-left" /></template>
