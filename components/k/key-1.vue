<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/uz5clsphv.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="uz5clsphv"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lineicons:key-1" /></template>
