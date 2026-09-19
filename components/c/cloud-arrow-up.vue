<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/lf457i13j.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="lf457i13j"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="heroicons:cloud-arrow-up" /></template>
