<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/wsl2jyqjy.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":12,"height":12};
const content = `<path class="wsl2jyqjy"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="dinkie-icons:circle" /></template>
