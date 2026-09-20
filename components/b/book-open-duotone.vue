<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/tb0ez_bdu.css';
import '../../css/j/j4olmxbwg.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="tb0ez_bdu"/><path class="j4olmxbwg"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lets-icons:book-open-duotone" /></template>
