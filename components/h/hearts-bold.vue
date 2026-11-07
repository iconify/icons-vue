<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/k_y09-bgq.css';
import '../../css/k/kxsg-jupr.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="k_y09-bgq"/><path class="kxsg-jupr"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:hearts-bold" /></template>
