<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/mn0p6fb3o.css';
import '../../css/m/mpgu6g9gp.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":25,"height":24};
const content = `<path class="mn0p6fb3o"/><path clip-rule="evenodd" class="mpgu6g9gp"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lineicons:chevron-right-circle" /></template>
