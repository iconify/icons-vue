<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/hhs1vzpxb.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="hhs1vzpxb"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-sharp:leaf-remix" /></template>
