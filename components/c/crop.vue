<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/vmxw-7_3j.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":15,"height":15};
const content = `<path class="vmxw-7_3j"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="radix-icons:crop" /></template>
