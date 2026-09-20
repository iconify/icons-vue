<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/waazunb1j.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="waazunb1j"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ri:forward-10-line" /></template>
