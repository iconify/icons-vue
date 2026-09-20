<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/d37wm6bfc.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="d37wm6bfc"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:house-lightning-bolt" /></template>
