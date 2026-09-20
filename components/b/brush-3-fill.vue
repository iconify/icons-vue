<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/m70158i_m.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="m70158i_m"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ri:brush-3-fill" /></template>
