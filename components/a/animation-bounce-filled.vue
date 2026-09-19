<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/patyb2g3j.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="patyb2g3j"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="boxicons:animation-bounce-filled" /></template>
