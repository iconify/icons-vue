<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/te67cnb-p.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="te67cnb-p"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="griddy-icons:clipboard-list" /></template>
