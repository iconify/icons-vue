<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/kghigabql.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="kghigabql"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:cheese-off" /></template>
