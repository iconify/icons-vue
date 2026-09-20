<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/wx45nfbbz.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="wx45nfbbz"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:firefox-fill" /></template>
