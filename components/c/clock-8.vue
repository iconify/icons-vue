<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/dm5rk2b2y.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="dm5rk2b2y"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:clock-8" /></template>
