<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/sypk8ebrs.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="sypk8ebrs"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="tdesign:arrow-left-down" /></template>
