<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/py9x-zbbz.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":25,"height":24};
const content = `<path clip-rule="evenodd" class="py9x-zbbz"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lineicons:dashboard-square-1" /></template>
