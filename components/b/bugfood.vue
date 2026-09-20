<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/f38yl6i_f.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="f38yl6i_f"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:bugfood" /></template>
