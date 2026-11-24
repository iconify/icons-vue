<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/f_slqp4cj.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="f_slqp4cj"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lucide-extended:funnel-filled" /></template>
