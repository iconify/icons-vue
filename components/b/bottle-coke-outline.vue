<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/o4z6nvb5j.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="o4z6nvb5j"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:bottle-coke-outline" /></template>
