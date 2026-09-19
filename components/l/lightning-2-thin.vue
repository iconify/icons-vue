<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/smy76dmek.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="smy76dmek"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconamoon:lightning-2-thin" /></template>
