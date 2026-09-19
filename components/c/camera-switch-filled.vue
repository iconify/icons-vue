<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/k6kt_2byq.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="k6kt_2byq"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="boxicons:camera-switch-filled" /></template>
