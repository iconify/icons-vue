<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/brjgsq-7m.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="brjgsq-7m"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="eva:arrow-back-fill" /></template>
