<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/bnq2lebro.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="bnq2lebro"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:letter-k-circle-outline" /></template>
