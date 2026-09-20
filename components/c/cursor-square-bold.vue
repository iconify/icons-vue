<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/aj-_6jdwt.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="aj-_6jdwt"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:cursor-square-bold" /></template>
