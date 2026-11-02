<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/nx6e3qbzk.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="nx6e3qbzk"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:circle-power-fill" /></template>
