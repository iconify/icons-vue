<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/qvjq8_bqx.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="qvjq8_bqx"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ri:loader-3-fill" /></template>
