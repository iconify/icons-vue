<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/zenzxyzmw.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="zenzxyzmw"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:arrow-rotate-left" /></template>
