<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/cmoqc4wyo.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="cmoqc4wyo"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="token:igu" /></template>
