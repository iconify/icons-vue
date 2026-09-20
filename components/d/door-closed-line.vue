<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/vn0p08fcw.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="vn0p08fcw"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ri:door-closed-line" /></template>
