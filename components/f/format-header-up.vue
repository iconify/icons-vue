<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/qf7mrlbzz.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="qf7mrlbzz"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:format-header-up" /></template>
