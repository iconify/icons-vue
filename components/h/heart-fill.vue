<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/qzh9j_86w.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="qzh9j_86w"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="eva:heart-fill" /></template>
