<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/uen_p8-7q.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="uen_p8-7q"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:list-up-minimalistic-bold" /></template>
