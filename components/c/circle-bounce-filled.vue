<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/v1s0x6x-m.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="v1s0x6x-m"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lucide-extended:circle-bounce-filled" /></template>
