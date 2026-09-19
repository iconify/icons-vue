<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/iy-qsfb_j.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="iy-qsfb_j"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="boxicons:angry-filled" /></template>
