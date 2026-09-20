<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/iitqzl8zc.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":14,"height":14};
const content = `<path clip-rule="evenodd" class="iitqzl8zc"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-flex:3d-rotate-1-remix" /></template>
