<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/guhgj0rvq.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="guhgj0rvq"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="token:fil" /></template>
