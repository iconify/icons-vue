<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/xl9r12-lw.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="xl9r12-lw"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-cyber:book-pencil" /></template>
