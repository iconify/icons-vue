<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/fihun-14b.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="fihun-14b"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="majesticons:church" /></template>
