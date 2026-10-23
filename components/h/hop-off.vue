<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/ijnwu_bsq.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ijnwu_bsq"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="vadivam:hop-off" /></template>
