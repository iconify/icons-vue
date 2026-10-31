<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/ql0sogb0x.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="ql0sogb0x"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lucide-extended:circle-letter-x-filled" /></template>
