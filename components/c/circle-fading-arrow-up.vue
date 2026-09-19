<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/yjbsh1btt.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="yjbsh1btt"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="hugeicons:circle-fading-arrow-up" /></template>
