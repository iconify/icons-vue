<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/p41bm-bqp.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="p41bm-bqp"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="majesticons:library-line" /></template>
