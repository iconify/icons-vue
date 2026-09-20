<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/mo1y_5kgv.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="mo1y_5kgv"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ri:dice-2-line" /></template>
