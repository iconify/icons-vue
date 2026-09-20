<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/l-c_r3bqt.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="l-c_r3bqt"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="majesticons:forward-circle" /></template>
