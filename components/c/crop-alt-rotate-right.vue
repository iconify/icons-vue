<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/hi24fmf5u.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="hi24fmf5u"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uil:crop-alt-rotate-right" /></template>
