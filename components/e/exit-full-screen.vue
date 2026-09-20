<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/uq-nx2bdn.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":15,"height":15};
const content = `<path class="uq-nx2bdn"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="radix-icons:exit-full-screen" /></template>
