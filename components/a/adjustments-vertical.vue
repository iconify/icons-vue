<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/c3cn5cb0x.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="c3cn5cb0x"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="heroicons:adjustments-vertical" /></template>
