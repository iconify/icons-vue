<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/z1lmm6bnz.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="z1lmm6bnz"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:letter-v-circle" /></template>
