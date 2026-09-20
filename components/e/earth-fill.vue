<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/iuldexbvf.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="iuldexbvf"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:earth-fill" /></template>
