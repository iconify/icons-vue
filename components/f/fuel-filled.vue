<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/fncit8v1y.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="fncit8v1y"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lucide-extended:fuel-filled" /></template>
