<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/eje08obor.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="eje08obor"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="prime:chevron-up" /></template>
