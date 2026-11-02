<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/kyjsuvhlw.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="kyjsuvhlw"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:enter-door-fill" /></template>
