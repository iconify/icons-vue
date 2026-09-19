<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/jesqx4bps.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="jesqx4bps"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="akar-icons:arrow-down-left" /></template>
