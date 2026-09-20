<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/gnxf60wjv.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="gnxf60wjv"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lineicons:adonis" /></template>
