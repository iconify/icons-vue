<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/ldkpy_bky.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ldkpy_bky"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="guidance:access-to-low-vision" /></template>
