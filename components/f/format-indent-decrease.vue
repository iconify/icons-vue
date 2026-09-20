<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/ksi8u2bfj.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ksi8u2bfj"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:format-indent-decrease" /></template>
