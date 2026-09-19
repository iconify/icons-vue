<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/m25gnw5fq.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="m25gnw5fq"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="flowbite:mail-box-outline" /></template>
