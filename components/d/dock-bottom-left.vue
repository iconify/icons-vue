<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/f9sq7n4kc.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="f9sq7n4kc"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="boxicons:dock-bottom-left" /></template>
