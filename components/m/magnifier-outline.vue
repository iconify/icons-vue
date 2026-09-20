<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/hd9w4b9sz.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="hd9w4b9sz"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:magnifier-outline" /></template>
