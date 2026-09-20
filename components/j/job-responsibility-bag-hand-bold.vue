<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/fmd_g055q.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="fmd_g055q"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-ultimate:job-responsibility-bag-hand-bold" /></template>
