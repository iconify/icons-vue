<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/r4y6mmu1p.css';
import '../../css/r/rc6lwuj7v.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="duoicon-secondary-layer r4y6mmu1p"/><path class="duoicon-primary-layer rc6lwuj7v"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="duo-icons:align-bottom" /></template>
