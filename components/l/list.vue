<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/kx1tyybho.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="kx1tyybho"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="struq:list" /></template>
