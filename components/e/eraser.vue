<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/sl0il1grl.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":15,"height":15};
const content = `<path class="sl0il1grl"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="radix-icons:eraser" /></template>
