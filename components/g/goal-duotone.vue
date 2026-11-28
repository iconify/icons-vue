<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/vw64u_b5h.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="primary vw64u_b5h"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconaut:goal-duotone" /></template>
